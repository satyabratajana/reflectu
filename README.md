# reflectu
<section id="wrapper">
		
        <div class="wos-header">
            <h1 style="text-align:center; margin-bottom:0">Generate Hyperlinks</h1>
            <h4 style="text-align:center; margin-top:0"><a href="http://www.wosgroup.com">Wosgroup</a></h4>
            
            <div class="wos-nav">
                <a href="#genhyp">Generate Hyperlinks</a>
                <a href="#makecom">Make Comment</a>
                <a href="#linkopen">Links Open</a>
            </div><!-- .wos-nav -->
            
            <div class="wos-page-count">
				<script type="text/javascript" src="http://services.webestools.com/cpt_pages_views/23165-19-6.js"></script>
            </div><!-- .wos-page-count -->
            
        </div><!-- .wos-header -->
	<div class="wos-content">
    	
        <div id="genhyp" class="wos-section">
            <div style="width:48%; float:left">
            <h3 style="text-align:center;">Links</h3>
            <textarea name="sometextarea" rows="10" style="width:100%"></textarea>
            </div>
            
            <div style="width:48%; float:right">
            <h3 style="text-align:center;">Keywords</h3>
            <textarea name="sometextarea2" rows="10" style="width:100%"></textarea>
            
            </div>
            
            <div style="clear:both"></div>
            
            <br/><br/>
            
            <button type="button" id="gen">Generate Hyperlinks</button>
            
            
            <p><strong>Total Links:</strong> <span id="tl"></span></p>
            <p><strong>Total Keywords:</strong> <span id="keyw"></span></p>
            
            
            <!--<div id="res"></div>-->
            <div class="wos_row cfix">
                <div class="col-50 fleft">
                    <textarea id="res" rows="12"></textarea>
                </div><!-- .col-50 -->
                <div class="col-50 fright">
                    <textarea id="res2" rows="12"></textarea>
                </div><!-- .col-50 -->
            
            </div><!-- .wos_row -->
        </div><!-- .wos-section -->
        
        <div id="makecom" class="wos-section">
            <p><strong>Make Comment:</strong></p>
            <div class="wos_row cfix">
                <div class="col-50 fleft">
                    <textarea id="mcom" name="mcom" rows="12"></textarea>
                </div><!-- .col-50 -->
                <div class="col-50 fright">
                    <div id="mcomres" class="boredr-box"></div>
                </div><!-- .col-50 -->
            
            </div><!-- .wos_row -->
            <br/>
            <button type="button" id="genMcom">Generate Comment</button>
            <br/><br/>
        </div><!-- .wos-section -->
        
        <div id="linkopen" class="wos-section">
            <p><strong>Links open in new Tabs: (Chrome setting: Goto chrome settings. click content settings button. scroll down and find Pop-ups and click Allaow all sites to show pop-ups).</strong> <span id="keyw"></span></p>
            
            
            <!--<div id="res"></div>-->
            <div class="wos_row cfix">
                <div class="">
                    <textarea id="openLinksTxt" name="openLinksTxt" rows="12"></textarea>
                </div><!--  -->
            
            </div><!-- .wos_row -->
            
            <button type="button" id="openLink">Open Links on new tabs.</button>
		</div><!-- .wos-section -->
            
	</div><!-- .wos-content --> 
    
