<!DOCTYPE html>
<html lang="en">
	<head>
		<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
		<title>Xây dựng website</title>
		<link rel="stylesheet" type="text/css" href="css/style.css">
		
		<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
		<script type="text/javascript" src="js/jquery.js"></script>
		<script type="text/javascript" src="js/wowslider.js"></script>
		<script type="text/javascript" src="js/script.js"></script>
		<script type="text/javascript" src="js/bootstrap.min.js"></script>
	</head>
	<body>
		<div class="container">
			<div class="row">
                 <div class="col-lg-12 col-md-12 col-xs-12 col-sm-12" id="header">
                    <div id="logo">
                        <p><img src="#"></p>
                    </div>
                 	<div id="menu">
                 		<ul id="menu_top">
                 			<li><a href="">Trang chủ</a></li>
                 			<li><a href="">Giới thiệu</a></li>
                 			<li><a href="">Thể thao</a></li>
                 			<li><a href="">Giáo dục</a></li>
                 			<li><a href="">Pháp luật</a></li>
                 			<li><a href="">Giải trí</a></li>
                 			<li><a href="">Xã hội</a></li>
                 			<li><a href="">Thế giới</a></li>
                 			<li><a href="">Sự kiện</a></li>
                 			<li><a href="">Liên hệ</a></li>
                 		</ul>
                 		<div class="clearfix"></div>
                 		<div id="search">
                 			<form name="frmsearch" method="POST" action="">
                 				<input type="text" name="ten" value="" placeholder="Tìm kiếm từ khóa">
                 				<input type="submit" name="submit" value="Tìm kiếm">
                 			</form>		
                 		</div>
                 	</div>
                 </div>
			</div>
			
			<div class="row">
				<div class="col-lg-3 col-md-3 col-sm-3 col-xs-3" id="left">
					<div class="box">
                         <div class="box_top">
                         	<p>Hỗ trợ trực tuyến</p>		
                         </div>
                         <div class="box_main">
                         	<div id="support">
	                        	<p><a href=""><img src="images/yahoo.png"></a><a href=""><img src="images/skype.png"></a></p> 	
	                        	<p>Hotline:&nbsp;<span>0919 405 624 - 0989 493 036</span></p>
	                        	<p>Email:&nbsp;hotro@ttm.edu.vn</p>
                        	</div>
                         </div>
					</div>
					<div class="box">
                         <div class="box_top">
                         	<p>Video</p>		
                         </div>
                         <div class="box_main">
                         	<div id="video">
	                        	<div id="content_video">
                                     <iframe width="100%" height="162px" class="embed-player" src="http://www.youtube.com/embed/" frameborder="0" allowfullscreen></iframe>
                                        <br />
                						<ul class="list-video">
                                            <li><a style="cursor:pointer;" title="E_Kh9dX_kGY"><i class="fa fa-caret-right fw"></i>&nbsp;Ái tính chủ diễn</a></li>
                                            <li><a style="cursor:pointer;" title="f5d50HEvR7I"><i class="fa fa-caret-right fw"></i>&nbsp;Video chả mực chiên</a></li>
                                        <script>                        
					                        $(document).ready(function(){
					                            $('.list-video li').click(function(){
					                                $(this).parent().siblings('.embed-player').attr('src','http://www.youtube.com/embed/'+$(this).children('a').attr('title'));                                     
					                            });
					                        });
					                    </script>
                						</ul>
                					<div class="clearfix"></div>
                				</div>
            					<div class="clearfix"></div>
                        	</div>
                         </div>
					</div>
					<div class="box">
                         <div class="box_top">
                         	<p>Bài viết mới nhất</p>		
                         </div>
                         <div class="box_main">
                         	<ul id="baiviet_l">
	                        	<li><a href="">Tin mới 1</a></li>
	                        	<li><a href="">Tin mới 1</a></li>
	                        	<li><a href="">Tin mới 1</a></li>
	                        	<li><a href="">Tin mới 1</a></li>
	                        	<li><a href="">Tin mới 1</a></li>	
                        	</ul>
                         </div>
					</div>	
				</div>
				<div class="col-lg-9 col-md-9 col-sm-9 col-xs-9" id="center">
					<div class="box_center">
                         <div class="box_center_top">
                            <div class="box_center_top_l">
                                <a href="">Pháp luật</a>     
                            </div>
                            <div class="box_center_top_r"></div>
                            <div class="clearfix"></div>
                         </div>
                         <div class="box_center_main">
                            <div class="row">
                                <div class="col-lg-4 col-md-4 col-sm-4 col-xs-4 tinhome_item">
                                    <a href="" class="tinhome_item_img"><img src="images/tin1.jpg"></a>
                                    <a href="" class="tinhome_item_name">Hoàng Thiên giúp Việt Nam thắng Indonesia</a>      
                                </div>
                                <div class="col-lg-4 col-md-4 col-sm-4 col-xs-4 tinhome_item">
                                    <a href="" class="tinhome_item_img"><img src="images/tin1.jpg"></a>
                                    <a href="" class="tinhome_item_name">Hoàng Thiên giúp Việt Nam thắng Indonesia</a>      
                                </div>
                                <div class="col-lg-4 col-md-4 col-sm-4 col-xs-4 tinhome_item">
                                    <a href="" class="tinhome_item_img"><img src="images/tin1.jpg"></a>
                                    <a href="" class="tinhome_item_name">Hoàng Thiên giúp Việt Nam thắng Indonesia</a>      
                                </div>
                            </div>  
                         </div>
                    </div>
					<div class="box_center">
                         <div class="box_center_top">
                            <div class="box_center_top_l">
                                <a href="">Thể thao</a>     
                            </div>
                            <div class="box_center_top_r"></div>
                            <div class="clearfix"></div>
                         </div>
                         <div class="box_center_main">
                            <div class="row">
                                <div class="col-lg-4 col-md-4 col-sm-4 col-xs-4 tinhome_item">
                                    <a href="" class="tinhome_item_img"><img src="images/tin1.jpg"></a>
                                    <a href="" class="tinhome_item_name">Hoàng Thiên giúp Việt Nam thắng Indonesia</a>      
                                </div>
                                <div class="col-lg-4 col-md-4 col-sm-4 col-xs-4 tinhome_item">
                                    <a href="" class="tinhome_item_img"><img src="images/tin1.jpg"></a>
                                    <a href="" class="tinhome_item_name">Hoàng Thiên giúp Việt Nam thắng Indonesia</a>      
                                </div>
                                <div class="col-lg-4 col-md-4 col-sm-4 col-xs-4 tinhome_item">
                                    <a href="" class="tinhome_item_img"><img src="images/tin1.jpg"></a>
                                    <a href="" class="tinhome_item_name">Hoàng Thiên giúp Việt Nam thắng Indonesia</a>      
                                </div>
                            </div>  
                         </div>
                    </div>
                    <div class="box_center">
                         <div class="box_center_top">
                            <div class="box_center_top_l">
                                <a href="">Giải trí</a>     
                            </div>
                            <div class="box_center_top_r"></div>
                            <div class="clearfix"></div>
                         </div>
                         <div class="box_center_main">
                            <div class="row">
                                <div class="col-lg-4 col-md-4 col-sm-4 col-xs-4 tinhome_item">
                                    <a href="" class="tinhome_item_img"><img src="images/tin1.jpg"></a>
                                    <a href="" class="tinhome_item_name">Hoàng Thiên giúp Việt Nam thắng Indonesia</a>      
                                </div>
                                <div class="col-lg-4 col-md-4 col-sm-4 col-xs-4 tinhome_item">
                                    <a href="" class="tinhome_item_img"><img src="images/tin1.jpg"></a>
                                    <a href="" class="tinhome_item_name">Hoàng Thiên giúp Việt Nam thắng Indonesia</a>      
                                </div>
                                <div class="col-lg-4 col-md-4 col-sm-4 col-xs-4 tinhome_item">
                                    <a href="" class="tinhome_item_img"><img src="images/tin1.jpg"></a>
                                    <a href="" class="tinhome_item_name">Hoàng Thiên giúp Việt Nam thắng Indonesia</a>      
                                </div>
                            </div>  
                         </div>
                    </div>						
				</div>				
			</div>
		</div>
	</div>
	<div id="bg_footer">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12" id="footer">
                    <p>Bản quyền 2016 thuộc về Vũ Văn Tùng</p>
                    <p>Địa chỉ:&nbsp;Đằng Lâm - Hải An - Hải Phòng</p>
                    <p>Điện thoại:&nbsp;01664.295.022</p>
                    <p>Email:tungvu90@gmail.com</p>                    
                </div>
            </div>
        </div>
	</div>
	</body>
</html>
