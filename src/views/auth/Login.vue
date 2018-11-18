<template>
     <div class="main">
      <div class="col-md-4 offset-md-4">
			<div class="modal-header">				
				<h4 class="modal-title">Sign In</h4>
			</div>
			<div class="modal-body">
				<form action="" method="post">
                 <div class="form-group">
                        <div class="input-group mb-3">
                            <div class="input-ico">
                                <div class="input-group-prepend">
                                    <span class="input-group-text" id="basic-addon1"><i class="ion-ios-contact"></i></span>
                                </div>
                            </div>
                            <input type="text" spellcheck="false" class="cust-input-field"  placeholder="Username">
                        </div>
                    </div>
                    <div class="form-group">
                        <div class="input-group mb-3">
                            <div class="input-ico">
                                <div class="input-group-prepend">
                                    <span class="input-group-text" id="basic-addon1"><i class="ion-ios-lock"></i></span>
                                </div>
                            </div>
                            <input type="password" spellcheck="false" class="cust-input-field" placeholder="Password">
                        </div>
                    </div>
					<div class="form-group">
						<button type="submit" class="btn sign-in-btn btn-success btn-block btn-sm">Sign In</button>
					</div>
				</form>
			</div>
		</div>
    </div>
</template>