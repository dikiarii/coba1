<body class="hold-transition login-page">
<div class="login-box">
  <div class="login-logo">
    <div style="font-size: 23px;"><b> Beauty n Dream </b></div>
  </div>
  <!-- /.login-logo -->
  <div class="login-box-body">

    <form action="<?php echo base_url('auth/login'); ?>" method="POST">
      <div class="form-group has-feedback">
        <!--<input type="email" class="" placeholder="Email"> -->
        <input type="text" name="username" class="form-control" placeholder="Nama User" id="active" autocomplete="off">
        <span class="glyphicon glyphicon-envelope form-control-feedback"></span>
      </div>
      <div class="form-group has-feedback">
        <input type="password" name="password" class="form-control" placeholder="Kata Sandi" autocomplete="off">
        <span class="glyphicon glyphicon-lock form-control-feedback"></span>
      </div>
      <div class="row">
        <!-- /.col -->
        <div class="col-xs-4">
          <input type="submit" name="submit" class="btn btn-primary btn-block btn-flat" value="Masuk" >
        </div>
        <!-- /.col -->
      </div>
    </form>
  </div>
  <!-- /.login-box-body -->
</div>
<!-- /.login-box -->