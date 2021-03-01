
<svg fill="none" viewBox="0 0 800 400" width="800" height="400" xmlns="http://www.w3.org/2000/svg">
	<foreignObject width="100%" height="100%">
		<div xmlns="http://www.w3.org/1999/xhtml">
			<style>
				@keyframes animate {

				  0%{
				    transform: translateY(0) rotate(0deg);
				    opacity: 1;
				    border-radius: 0;
				  }

				  100%{
				    transform: translateY(-1000px) rotate(720deg);
				    opacity: 0;
				    border-radius: 50%;
				  }

				}

				.area{
				  background: linear-gradient(#fca4a4, #FFD3D6);
				  width: 100%;
				  height:100%;
				  position: fixed;


				}
				.circles{
				  position: absolute;
				  top: 0;
				  left: 0;
				  width: 100%;
				  height: 100%;
				  overflow: hidden;
				}

				.circles li{
				  position: absolute;
				  display: block;
				  list-style: none;
				  width: 20px;
				  height: 20px;
				  background: rgba(255, 255, 255, 0.2);
				  animation: animate 25s linear infinite;
				  bottom: -150px;

				}

				.circles li:nth-child(1){
				  left: 25%;
				  width: 80px;
				  height: 80px;
				  animation-delay: 0s;
				}


				.circles li:nth-child(2){
				  left: 10%;
				  width: 20px;
				  height: 20px;
				  animation-delay: 2s;
				  animation-duration: 12s;
				}

				.circles li:nth-child(3){
				  left: 70%;
				  width: 20px;
				  height: 20px;
				  animation-delay: 4s;
				}

				.circles li:nth-child(4){
				  left: 40%;
				  width: 60px;
				  height: 60px;
				  animation-delay: 0s;
				  animation-duration: 18s;
				}

				.circles li:nth-child(5){
				  left: 65%;
				  width: 20px;
				  height: 20px;
				  animation-delay: 0s;
				}

				.circles li:nth-child(6){
				  left: 75%;
				  width: 110px;
				  height: 110px;
				  animation-delay: 3s;
				}

				.circles li:nth-child(7){
				  left: 35%;
				  width: 150px;
				  height: 150px;
				  animation-delay: 7s;
				}

				.circles li:nth-child(8){
				  left: 50%;
				  width: 25px;
				  height: 25px;
				  animation-delay: 15s;
				  animation-duration: 45s;
				}

				.circles li:nth-child(9){
				  left: 20%;
				  width: 15px;
				  height: 15px;
				  animation-delay: 2s;
				  animation-duration: 35s;
				}

				.circles li:nth-child(10){
				  left: 85%;
				  width: 150px;
				  height: 150px;
				  animation-delay: 0s;
				  animation-duration: 11s;
				}
				/* latin-ext */
				@font-face {
				    font-family: 'Just Me Again Down Here';
				    font-style: normal;
				    font-weight: 400;
				    font-display: swap;
				    src: url(https://fonts.gstatic.com/s/justmeagaindownhere/v12/MwQmbgXtz-Wc6RUEGNMc0QpRrfUh2hSdBBMoAtwOtKHScOfhdJ0.woff2) format('woff2');
				    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
				}
				/* latin */
				@font-face {
				    font-family: 'Just Me Again Down Here';
				    font-style: normal;
				    font-weight: 400;
				    font-display: swap;
				    src: url(https://fonts.gstatic.com/s/justmeagaindownhere/v12/MwQmbgXtz-Wc6RUEGNMc0QpRrfUh2hSdBBMoAtwAtKHScOfh.woff2) format('woff2');
				    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
				}
				/* latin-ext */
				@font-face {
				    font-family: 'Sacramento';
				    font-style: normal;
				    font-weight: 400;
				    font-display: swap;
				    src: url(https://fonts.gstatic.com/s/sacramento/v8/buEzpo6gcdjy0EiZMBUG4CMf_f5Iai0Ycw.woff2) format('woff2');
				    unicode-range: U+0100-024F, U+0259, U+1E00-1EFF, U+2020, U+20A0-20AB, U+20AD-20CF, U+2113, U+2C60-2C7F, U+A720-A7FF;
				}
				/* latin */
				@font-face {
				    font-family: 'Sacramento';
				    font-style: normal;
				    font-weight: 400;
				    font-display: swap;
				    src: url(https://fonts.gstatic.com/s/sacramento/v8/buEzpo6gcdjy0EiZMBUG4C0f_f5Iai0.woff2) format('woff2');
				    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
				}
				.fullscreenDiv {
				    background-color:  transparent;
				    width: 650px;
				    height: 750px;
				    top: 10px;
				    left: 50%;
				    margin-left: -325px;
				    position: absolute;
				}
				
				.name {
				    position: absolute;
				    width: 500px;
				    height: 120px;
				    top: 150px;
				    left: 50%;
				    font-size:90px;
				    text-align: center;

				    font-family: Sacramento,cursive;
				    color: #fbebeb;
				    margin-left: -250px; /* margin is -0.5 * dimension */
				    margin-top: -60px;

				}
				.tagline {
				    position: absolute;
				    width: 500px;
				    height: 50px;
				    top: 250px;
				    left: 50%;
				    font-size:35px;
				    text-align: center;
				    font-family: "Just Me Again Down Here",cursive;
				    color: #fbebeb;
				    margin-left: -250px; /* margin is -0.5 * dimension */
				    margin-top: -25px;

				}

				
				

			</style>
			<div class="area" >
				<ul class="circles">
					<li></li>
					<li></li>
					<li></li>
					<li></li>
					<li></li>
					<li></li>
					<li></li>
					<li></li>
					<li></li>
					<li></li>
				</ul>
			</div >
			<div class="fullscreenDiv">
			    	<div class="name">Johan Naizu
			    	</div>
			    	<div class="tagline">A Software Developer
			    	</div>
			    	
			</div>
		</div>
	</foreignObject>
</svg>
