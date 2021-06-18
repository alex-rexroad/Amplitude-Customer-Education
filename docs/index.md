
<!DOCTYPE html>
<html dir="ltr" lang="en-US">
<head>
  <meta charset="utf-8" />
  <!-- v17682 -->

  <title>[org name]</title>

  <meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="hc:meta:server:zneQRlfZb5cgvxE+O0u0adDVSpYBWL5w2PntgHi9EzW7TXsV7v+vVzq4ZvlP1DcQHjrYyWmlLjZDcSdmZ8ZLuA==" />

  <link rel="canonical" href="https://help.[org name].com/hc/en-us" />
<link rel="alternate" hreflang="en" href="https://help.[org name].com/hc/en-us" />

  <link rel="stylesheet" media="all" href="//static.zdassets.com/hc/assets/application-ebbf4a70487f9466c9be47bf4b6055f6.css" id="stylesheet" />
    <!-- Entypo pictograms by Daniel Bruce — www.entypo.com -->
    <link rel="stylesheet" media="all" href="//static.zdassets.com/hc/assets/theming_v1_support-7eacdab8920220a42cfc91404f4ed182.css" />
  <link rel="stylesheet" type="text/css" href="//p13.zdassets.com/hc/theming_assets/667553/68397/style.css?digest=360372089352" />

  <link rel="shortcut icon" type="image/x-icon" href="//theme.zdassets.com/theme_assets/667553/afbffbd34e14d3592c8407254c7ce8417e086adb.ico" />

    <script src="//static.zdassets.com/hc/assets/jquery-d5395f0b7ac5027403fc17855c46dbfc.js"></script>
    
    

  <meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0" name="viewport" />
<link href="https://vjs.zencdn.net/5.2.1/video-js.css" rel="stylesheet">
<script src="https://vjs.zencdn.net/5.2.1/video.js"></script>
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/algoliasearch.zendesk-hc/2/algoliasearch.zendesk-hc.min.css">
<script type="text/javascript" src="//cdn.jsdelivr.net/algoliasearch.zendesk-hc/2/algoliasearch.zendesk-hc.min.js"></script>
<script type="text/javascript">
  algoliasearchZendeskHC({
    applicationId: 'MRQCO3H43U',
    apiKey: '0a5d311538cabe50f577a0c34b97c2c0',
    subdomain: 'amplitude'
  });
</script>
<!-- Amplitude JavaScript SDK -->
<script type="text/javascript">
(function(e,t){var n=e.amplitude||{_q:[],_iq:{}};var r=t.createElement("script")
;r.type="text/javascript"
;r.integrity="sha384-a+mq7tiLwde/00Oc7avFHLn/ttGfdAq1rtZc7u97SEzIiyYoT2IsOKWCkAThwdEu"
;r.crossOrigin="anonymous";r.async=true
;r.src="https://cdn.[org name].com/libs/[org name]-5.3.0-min.gz.js"
;r.onload=function(){if(!e.[org name].runQueuedFunctions){
console.log("[[org name]] Error: could not load SDK")}}
;var i=t.getElementsByTagName("script")[0];i.parentNode.insertBefore(r,i)
;function s(e,t){e.prototype[t]=function(){
this._q.push([t].concat(Array.prototype.slice.call(arguments,0)));return this}}
var o=function(){this._q=[];return this}
;var a=["add","append","clearAll","prepend","set","setOnce","unset"]
;for(var u=0;u<a.length;u++){s(o,a[u])}n.Identify=o;var c=function(){this._q=[]
;return this}
;var l=["setProductId","setQuantity","setPrice","setRevenueType","setEventProperties"]
;for(var p=0;p<l.length;p++){s(c,l[p])}n.Revenue=c
;var d=["init","logEvent","logRevenue","setUserId","setUserProperties","setOptOut","setVersionName","setDomain","setDeviceId","setGlobalUserProperties","identify","clearUserProperties","setGroup","logRevenueV2","regenerateDeviceId","groupIdentify","onInit","logEventWithTimestamp","logEventWithGroups","setSessionId","resetSessionId"]
;function v(e){function t(t){e[t]=function(){
e._q.push([t].concat(Array.prototype.slice.call(arguments,0)))}}
for(var n=0;n<d.length;n++){t(d[n])}}v(n);n.getInstance=function(e){
e=(!e||e.length===0?"$default_instance":e).toLowerCase()
;if(!n._iq.hasOwnProperty(e)){n._iq[e]={_q:[]};v(n._iq[e])}return n._iq[e]}
;e.amplitude=n})(window,document);

(function () {
  var growth_apiKey = "9ff40c01dfb3f736760a5ecfc5478e8a";
  var growth_instanceName = "growth_sandbox";
  var zendesk_apiKey = "c8c2cd4cc007f506277b943e6c35a13a";
  var growthDeviceId = '';

  amplitude.getInstance(growth_instanceName).init(growth_apiKey, null, {logLevel: 'INFO'}, function(growthInstance) {
    growthDeviceId = growthInstance.options.deviceId;
  });

  amplitude.getInstance().init(zendesk_apiKey, null, { logLevel: 'INFO' }, function(zendeskInstance) {
    zendeskInstance.setDeviceId(growthDeviceId);
  });
}());
 
</script>

  <script type="text/javascript" src="//p13.zdassets.com/hc/theming_assets/667553/68397/script.js?digest=360372089352"></script>
</head>
<body class="">
  <div id="navbar-container" data-navbar="{&quot;locale&quot;:&quot;en-us&quot;,&quot;locale_direction&quot;:&quot;ltr&quot;,&quot;show_brand_settings_link&quot;:false,&quot;avatar_url&quot;:&quot;https://help.[org name].com/system/photos/3602/6536/4312/profile_image_382372458451_667553.png&quot;,&quot;current_brand&quot;:&quot;[org name]&quot;,&quot;brand_selector_payload&quot;:{&quot;brands&quot;:[],&quot;brand_settings_url&quot;:&quot;https://[org name].zendesk.com/agent/admin/brands&quot;,&quot;brand_settings_label&quot;:&quot;Brand settings&quot;},&quot;user_dropdown_items&quot;:[{&quot;type&quot;:&quot;item&quot;,&quot;url&quot;:&quot;/access/return_to?return_to=https://[org name].zendesk.com/agent/users/382372458451&quot;,&quot;label&quot;:&quot;View profile&quot;,&quot;target&quot;:&quot;_blank&quot;,&quot;options&quot;:{&quot;identifier&quot;:&quot;user_profile&quot;,&quot;name&quot;:&quot;Alexander Rexroad&quot;,&quot;avatar&quot;:&quot;https://help.[org name].com/system/photos/3602/6536/4312/profile_image_382372458451_667553.png&quot;}},{&quot;type&quot;:&quot;separator&quot;},{&quot;type&quot;:&quot;item&quot;,&quot;url&quot;:&quot;/hc/admin/plan&quot;,&quot;label&quot;:&quot;Upgrade account&quot;,&quot;options&quot;:{&quot;identifier&quot;:&quot;upgrade_cta&quot;}},{&quot;type&quot;:&quot;item&quot;,&quot;url&quot;:&quot;https://support.zendesk.com/forums/1848-Product-Feedback&quot;,&quot;label&quot;:&quot;Give feedback&quot;,&quot;target&quot;:&quot;_blank&quot;},{&quot;type&quot;:&quot;item&quot;,&quot;url&quot;:&quot;https://support.zendesk.com/hc/en-us/sections/360004109213&quot;,&quot;label&quot;:&quot;Get help&quot;,&quot;target&quot;:&quot;_blank&quot;},{&quot;type&quot;:&quot;item&quot;,&quot;url&quot;:&quot;https://www.zendesk.com/company/customers-partners/privacy-policy/&quot;,&quot;label&quot;:&quot;Privacy policy&quot;,&quot;target&quot;:&quot;_blank&quot;},{&quot;type&quot;:&quot;separator&quot;},{&quot;type&quot;:&quot;item&quot;,&quot;url&quot;:&quot;/access/logout?return_to=https%3A%2F%2Fhelp.[org name].com%2Fhc%2Fen-us&quot;,&quot;label&quot;:&quot;Sign out&quot;}],&quot;record_action_button&quot;:{&quot;label&quot;:&quot;&quot;,&quot;url&quot;:&quot;&quot;,&quot;target&quot;:&quot;&quot;,&quot;disabled&quot;:true},&quot;user_profile_button&quot;:{&quot;label&quot;:&quot;&quot;,&quot;url&quot;:&quot;&quot;,&quot;target&quot;:&quot;&quot;,&quot;disabled&quot;:true},&quot;user_identifier&quot;:&quot;7dcc5571f41d1722649916fa41797defdc7d8956&quot;,&quot;products_endpoint&quot;:&quot;https://[org name].zendesk.com/api/v2/products.json&quot;,&quot;product&quot;:&quot;guide&quot;,&quot;appearance_version&quot;:&quot;2.0&quot;,&quot;plan_information&quot;:{&quot;trial_active&quot;:false},&quot;general_dropdown_title&quot;:&quot;Add&quot;,&quot;general_dropdown_items&quot;:[{&quot;type&quot;:&quot;item&quot;,&quot;url&quot;:&quot;https://[org name].zendesk.com/knowledge/articles/new?brand_id=68397&quot;,&quot;label&quot;:&quot;Article&quot;},{&quot;type&quot;:&quot;item&quot;,&quot;url&quot;:&quot;https://[org name].zendesk.com/knowledge/sections/new?brand_id=68397&quot;,&quot;label&quot;:&quot;Section&quot;},{&quot;type&quot;:&quot;item&quot;,&quot;url&quot;:&quot;https://help.[org name].com/hc/admin/categories/new&quot;,&quot;label&quot;:&quot;Category&quot;}],&quot;guide_admin_button&quot;:{&quot;label&quot;:&quot;Guide admin&quot;,&quot;url&quot;:&quot;https://[org name].zendesk.com/knowledge/lists/default/1?brand_id=68397&quot;}}" style="height: 50px;width: 100%;background-color: #fff;border-bottom: 1px solid #ddd;box-shadow: 0 0 20px 0 rgba(36, 83, 107, 0.15)"></div>
  

  <header class="header">
    <!-- Top Nav Bar -->
    <div class="logo">
        <a title="Home" href="/hc/en-us">
        <img src="//theme.zdassets.com/theme_assets/667553/80b5cc742cecbc306d0f75b736552ecfadf13ed4.svg" alt="Logo">
        </a>
    </div>
  
    <div class="nav-wrapper">
        <span class="icon-menu"></span>
        <nav class="user-nav" id="user-nav">
            
            
        </nav>
          <div id="user" class="user-info dropdown" data-helper="user_info">
  <div class="btn with-image dropdown-toggle" role="button">
    <img id="user-avatar" class="user-avatar" alt="Alex Rexroad" src="https://help.[org name].com/system/photos/3602/6536/4312/profile_image_382372458451_667553.png" />
    <span id="user-name">Alex Rexroad</span>
  </div>
  <div id="user-dropdown" class="dropdown-menu dropdown-menu-end dropdown-menu-caret" aria-expanded="false" role="menu">
    <div role="menu" id="user-menu">
  <a class="my-activities" href="/hc/en-us/requests" role="menuitem">
  My activities
</a>





    <a href="/access/logout?return_to=https%3A%2F%2Fhelp.[org name].com%2Fhc%2Fen-us" role="menuitem">Sign out</a>
</div>

  </div>
</div>


    </div>
  
    <!-- Anchor Links -->
    <script src="https://cdn.jsdelivr.net/anchorjs/3.2.2/anchor.min.js"></script>
    		
    <!-- Font Awesome Icons -->
    <script src="https://use.fontawesome.com/bb76f2b5e6.js"></script>
  
    <!-- Footer CSS -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css"></script>
  
    
<!-- Start of [org name] Zendesk Widget script -->
<script>/*<![CDATA[*/window.zEmbed||function(e,t){var n,o,d,i,s,a=[],r=document.createElement("iframe");window.zEmbed=function(){a.push(arguments)},window.zE=window.zE||window.zEmbed,r.src="javascript:false",r.title="",r.role="presentation",(r.frameElement||r).style.cssText="display: none",d=document.getElementsByTagName("script"),d=d[d.length-1],d.parentNode.insertBefore(r,d),i=r.contentWindow,s=i.document;try{o=s}catch(e){n=document.domain,r.src='javascript:var d=document.open();d.domain="'+n+'";void(0);',o=s}o.open()._l=function(){var e=this.createElement("script");n&&(this.domain=n),e.id="js-iframe-async",e.src="https://assets.zendesk.com/embeddable_framework/main.js",this.t=+new Date,this.zendeskHost="[org name].zendesk.com",this.zEQueue=a,this.body.appendChild(e)},o.write('<body onload="document._l();">'),o.close()}();
/*]]>*/</script>
<!-- End of [org name] Zendesk Widget script -->
   
</header>


  <main role="main">
    <script type="text/javascript">
  [org name].getInstance().logEvent('view home');
</script>

<section class="section hero">
  <div class="hero-inner">
    <form role="search" class="search search-full" data-search="" data-instant="true" autocomplete="off" action="/hc/en-us/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" /><input type="search" name="query" id="query" placeholder="Have a question? Ask or enter a search term here." autocomplete="off" aria-label="Have a question? Ask or enter a search term here." /></form>
  </div>
</section>

<div class="container">
  
  <!-- Top 3 buttons -->
  <section class="section">
    <ul class="buttons-list">
      <li>
        <a href="https://[org name].com/blog/category/inside-[org name]">
   				<div class="button-circle1"></div>
    			<p class="button-caption">Product Updates</p>
        </a>
     </li>
     <li>
        <a href="https://[org name].zendesk.com/hc/en-us/requests/new">
   				<div class="button-circle2"></div>
    			<p class="button-caption">Submit a Request</p>
       </a>
     </li>
     <li>
        <a href="https://www.productanalyticsplaybook.com/">
   				<div class="button-circle3"></div>
    			<p class="button-caption">Product Analytics Playbook</p>
       </a>
     </li>
    </ul>
  </section>
  
  <!-- Category buttons -->
  <section class="section knowledge-base">
    <section class="categories blocks">
      <ul class="blocks-list">
        
        
        
        
          <li class="blocks-item">
            <a href='/hc/en-us/categories/200409887-Getting-Started' class="blocks-item-link">
              
              	<img src="//theme.zdassets.com/theme_assets/667553/c8debe1afbfc9cfeaf0dc6797bebeca91ec66bb8.svg" />
              
              
              
              <h4 class="blocks-item-title">Getting Started</h4>
              <!-- <p class="blocks-item-description"></p> -->
            </a>
          </li>
        
        
        
        
        
        
        
          <li class="blocks-item">
            <a href='/hc/en-us/categories/115000290488-Technical-Resources' class="blocks-item-link">
              
              
              
              	<img src="//theme.zdassets.com/theme_assets/667553/a61402e576f38ce26b87fb55b200a9a5568a666e.svg" />
              
              <h4 class="blocks-item-title">Technical Resources</h4>
              <!-- <p class="blocks-item-description"></p> -->
            </a>
          </li>
        
        
        
        
        
        
        
          <li class="blocks-item">
            <a href='/hc/en-us/categories/204084067-Learning-Center' class="blocks-item-link">
              
              
              	<img src="//theme.zdassets.com/theme_assets/667553/cbe6a79bd1397b346af3cad620873166cc71d8f5.svg" />
              
              
              <h4 class="blocks-item-title">Learning Center</h4>
              <!-- <p class="blocks-item-description"></p> -->
            </a>
          </li>
        
        
        
        
        
        
      </ul>
      
    </section>
  </section>
  
  <!-- Popular Content -->
  <section class="section">
    <h5>Popular Content</h5>
    <ul class="popular-list">
      <li class="popular-list-item">
        <a href="https://[org name].zendesk.com/hc/en-us/articles/115003135607-Tracking-Unique-Users">Tracking Unique Users</a>
      </li>
      <li class="popular-list-item">
        <a href="https://[org name].zendesk.com/hc/articles/207108137-Introduction">Introduction & Getting Started</a>
      </li>
      <li class="popular-list-item">

        <a href="https://[org name].zendesk.com/hc/articles/204771828-HTTP-API">HTTP API</a>
      </li>
      <li class="popular-list-item">
        <a href="https://[org name].zendesk.com/hc/articles/205406607-SDKs">SDKs</a>
      </li>
      <li>
        <a href="https://[org name].zendesk.com/hc/en-us/articles/115000465251-Data-Taxonomy-Playbook">Data Taxonomy Playbook</a>
      </li>
      <li class="popular-list-item">
        <a href="https://[org name].zendesk.com/hc/en-us/articles/230290208-[org name]-2-0-Event-Segmentation">Event Segmentation</a>
      </li>
      <li class="popular-list-item">
        <a href="https://[org name].zendesk.com/hc/articles/235974707-[org name]-2-0-Webinar-Series">[org name] Seminars</a>
      </li>
      <li class="popular-list-item">
        <a href="https://[org name].zendesk.com/hc/en-us/articles/231881448-[org name]-2-0-Behavioral-Cohorts">Behavioral Cohorts</a>
      </li>
      <li class="popular-list-item">
        <a href="https://[org name].zendesk.com/hc/en-us/articles/115000959052">For Developers: Getting Started</a>
      </li>
    </ul>
  </section>

    <!-- 
      <section class="articles">
        <h5></h5>
        <ul class="article-list promoted-articles">
          
            <li class="promoted-articles-item">
              <a href="">
                
              </a>
            </li>
          
        </ul>
      </section>
    
  </section> -->

  <!-- 
    <section class="section community">
      <h5></h5>
      
        
      

      <div class="community-image"></div>
    </section>
   -->

  <!-- <section class="section activity">
    
  </section> -->
	
  <!-- Status Updates -->
  <br />
	<div class="container-full">
  	<img src="//theme.zdassets.com/theme_assets/667553/fb0bc07563f0e826669d47155811ddd1961be143.png
" height="24" width="24" style="margin-top:-4px;margin-right:2px;"/>Subscribe to server status updates:
  	<a href="http://status.[org name].com/">status.[org name].com</a>
  </div>
  <br />
  <br />
  <br />

</div>
  </main>

  <!-- <footer class="footer">
  <div class="footer-inner">
    

    <div class="footer-language-selector">
      
        <div class="dropdown language-selector" aria-haspopup="true">
          <a class="dropdown-toggle">
            
          </a>
          <span class="dropdown-menu dropdown-menu-end" role="menu">
            
              <a href="" dir="" rel="nofollow" role="menuitem">
                
              </a>
            
          </span>
        </div>
      
    </div>
  </div>
</footer> -->

<footer id="footer">
  <div class="container-fluid">
    <div class="row-flex">
      <nav class="col-xs-6 col-sm-4 col-md-2">
        <span class="footer-title">Company</span>
        <ul class="list-unstyled">
          <li><a href="https://[org name].com/company">About Us</a></li>
          <li><a href="https://[org name].com/behavioral-resources#press">Press</a></li>
          <li><a href="https://[org name].com/careers">Careers</a></li>
          <li><a href="https://[org name].com/engineering">Engineering</a></li>
          <li><a target="_blank" href="https://www.dropbox.com/sh/bftcgxfxtustlb3/AACYGOFY6EIEiXijWctVy5G9a?dl=0">Press Kit</a></li>
        </ul>
      </nav>
      <nav class="col-xs-6 col-sm-4 col-md-2">
        <span class="footer-title">Products</span>
        <ul class="list-unstyled">
          <li><a href="https://[org name].com/behavioral-analytics-platform">Product Analytics</a></li>
          <li><a href="https://[org name].com/taxonomy">Taxonomy</a></li>
          <li><a href="https://[org name].com/insight">Insight</a></li>
          <li><a href="https://[org name].com/scale">Scale</a></li>
          <li><a href="https://[org name].com/accounts">Accounts</a></li>
          <li><a href="https://[org name].com/pricing?ref=footer">Plans</a></li>
        </ul>
      </nav>
      <nav class="col-xs-6 col-sm-4 col-md-2">
        <span class="footer-title">Solutions</span>
        <ul class="list-unstyled">
          <li><a href="https://[org name].com/integrations">Integrations</a></li>
          <li><a href="https://[org name].com/cross-platform-analytics">Cross-platform</a></li>
          <li><a href="https://[org name].com/data-accessibility">Data Accessibility</a></li>
          <li><a href="https://[org name].com/real-time-analytics">Real-Time Analytics</a></li>
        </ul>
      </nav>
      <nav class="col-xs-6 col-sm-4 col-md-2">
        <span class="footer-title">FEATURES</span>
        <ul class="list-unstyled">
          <li><a href="https://[org name].com/funnels">Funnel Analysis</a></li>
          <li><a href="https://[org name].com/retention">Retention</a></li>
          <li><a href="https://[org name].com/behavioral-cohorts">Behavioral Cohorts</a></li>
          <li><a href="https://[org name].com/pathfinder">Pathfinder</a></li>
          <li><a href="https://[org name].com/compass">Compass</a></li>
        </ul>
      </nav>
      <nav class="col-xs-6 col-sm-4 col-md-2">
        <span class="footer-title">Resources</span>
        <ul class="list-unstyled">
          <li><a target="_blank" href="https://[org name].com/blog">Blog</a></li>
          <li><a target="_blank" href="https://[org name].zendesk.com/hc/en-us">Help Center</a></li>
          <li><a href="https://[org name].com/behavioral-resources">Learning</a></li>
          <li><a href="https://[org name].com/partners">Partners</a></li>
        </ul>
      </nav>
      <nav class="col-xs-6 col-sm-4 col-md-2">
        <span class="footer-title">Services & Support</span>
        <ul class="list-unstyled">
          <li><a target="_blank" href="https://status.[org name].com/">System Status</a></li>
          <li><a href="https://[org name].com/contact?ref=footer">Contact Us</a></li>
          <li><a href="https://[org name].com/signup?ref=footer">Try It Free</a></li>
        </ul>
      </nav>
    </div>

    <div class="footer-bottom">
      <ul class="list-inline">
        <li>© 2019 [org name], Inc. All rights reserved. [org name] is a registered trademark of [org name], Inc.</li>
        <li><a href="https://[org name].com/terms">Terms of Use</a></li>
        <li><a href="https://[org name].com/privacy">Privacy Policy</a></li>
        <li><a href="https://[org name].com/sitemap">Sitemap</a></li>
      </ul>
      <ul class="list-inline social-networks">
        <li><a href="https://twitter.com/[org name]" target="_blank" class="fa fa-twitter"></a></li>
        <li><a href="https://www.facebook.com/[org name]/" target="_blank" class="fa fa-facebook"></a></li>
        <li><a href="https://www.linkedin.com/company/[org name]-analytics" target="_blank" class="fa fa-linkedin"></a></li>
      </ul>
    </div>

  </div>

</footer>


  <!-- / -->
  
  <script src="//static.zdassets.com/hc/assets/en-us.0aa8fb06734a1c1977c3.js"></script>
  <script src="https://[org name].zendesk.com/auth/v2/host.js" data-brand-id="68397" data-return-to="https://help.[org name].com/hc/en-us" data-theme="hc" data-locale="en-us" data-auth-origin="68397,true,true"></script>

  <script type="text/javascript">
  /*

    Greetings sourcecode lurker!

    This is for internal Zendesk and legacy usage,
    we don't support or guarantee any of these values
    so please don't build stuff on top of them.

  */

  HelpCenter = {};
  HelpCenter.account = {"subdomain":"[org name]","environment":"production","name":"[org name]"};
  HelpCenter.user = {"identifier":"7dcc5571f41d1722649916fa41797defdc7d8956","email":"alex.rexroad@[org name].com","name":"Alex Rexroad","tags":[],"locale":"en-us","role":"manager","avatar_url":"https://help.[org name].com/system/photos/3602/6536/4312/profile_image_382372458451_667553.png","is_admin":false,"organizations":[{"name":"devinstestcompany4","default":"[org name].com","tags":["scholarship"],"isShared":false}],"groups":[{"name":"Support","default":true,"isActive":true}]};
  HelpCenter.internal = {"asset_url":"//static.zdassets.com/hc/assets/","web_widget_asset_composer_url":"https://static.zdassets.com/ekr/snippet.js","current_session":{"locale":"en-us","csrf_token":"hc:hcobject:server:0qQoqlGlIoTPT5Ixnldr6Bcdjh/zyPBYbWtyUTMOHsGnnsP56IPiRNVI5fbqyOiR2fIcQJs1YB7247i3LHVGTA==","shared_csrf_token":"TJV7d49wc9xDCQXLzMjTXNXUL1bw5CiJiM7ysZjeBRme4zpkMHxALD3GoDunL0kr"},"settings":{"article_sanitization_disabled":true,"zopim_enabled":true},"usage_tracking":{"event":"front_page_viewed","data":"BAh7BjoKX21ldGF7CzoPYWNjb3VudF9pZGkDoS8KOhNoZWxwX2NlbnRlcl9pZGkEDZ3sCzoNYnJhbmRfaWRpAy0LAToMdXNlcl9pZGwrCNOvLAdZADoOdXNlcl9yb2xlSSIMbWFuYWdlcgY6BkVUOgtsb2NhbGVJIgplbi11cwY7C1Q=--62c1a581fef2152460c3b302348aaa28709165bd","url":"https://help.[org name].com/hc/tracking/events?locale=en-us"},"current_record_id":null,"current_record_url":null,"current_record_title":null,"search_results_count":null,"current_text_direction":"ltr","current_brand_url":"https://[org name].zendesk.com","current_host_mapping":"help.[org name].com","current_path":null,"authentication_domain":"https://[org name].zendesk.com","show_autocomplete_breadcrumbs":true,"rollbar_config":{"enabled":true,"endpoint":"https://rollbar-us.zendesk.com/api/1/item/","accessToken":"731a5a953e9a4b7ab6cac9623f50c732","captureUncaught":true,"captureUnhandledRejections":true,"payload":{"environment":"production","client":{"javascript":{"source_map_enabled":true,"code_version":"aac69059fb4e5d4ce12d38efa280f6fe7d3be5e2","guess_uncaught_frames":true}}}},"user_info_changing_enabled":false,"has_user_profiles_enabled":false,"user_aliases_enabled":false,"has_anonymous_kb_voting":true,"has_multi_language_help_center":true,"mobile_device":false,"mobile_site_enabled":false,"show_at_mentions":false,"embeddables_config":{"embeddables_web_widget":false,"embeddables_connect_ipms":false},"base_domain":"zendesk.com","answer_bot_subdomain":"static","plans_url":"https://help.[org name].com/hc/admin/plan?locale=en-us","manage_content_url":"https://help.[org name].com/hc/admin/manage/pending?locale=en-us","arrange_content_url":"https://help.[org name].com/hc/admin/arrange_contents?locale=en-us","general_settings_url":"https://help.[org name].com/hc/admin/general_settings?locale=en-us","user_segments_url":"https://[org name].zendesk.com/knowledge/user_segments?brand_id=68397","has_community_enabled":false,"has_user_segments":true,"has_answer_bot_web_form_enabled":true,"billing_url":"/access/return_to?return_to=https://[org name].zendesk.com/admin/billing/subscription","has_answer_bot":true,"has_block_answer_bot_embeddable":false,"answer_bot_management_url":"/access/return_to?return_to=https://[org name].zendesk.com/agent/admin/answer_bot","is_account_owner":false,"theming_cookie_key":"hc-7dcc5571f41d1722649916fa41797defdc7d89561-preview","is_preview":false,"has_guide_user_segments_search":true,"has_alternate_templates":false,"arrange_articles_url":"https://[org name].zendesk.com/knowledge/arrange?brand_id=68397","article_verification_url":"https://[org name].zendesk.com/knowledge/verification?brand_id=68397","has_article_verification":false,"guide_language_settings_url":"https://help.[org name].com/hc/admin/language_settings?locale=en-us","docs_importer_url":"https://[org name].zendesk.com/knowledge/import_articles?brand_id=68397","community_settings_url":"https://[org name].zendesk.com/knowledge/community_settings?brand_id=68397","gather_plan_state":"subscribed","search_settings_url":"https://[org name].zendesk.com/knowledge/search_settings?brand_id=68397","has_multibrand_search_in_plan":false,"theming_api_version":1,"has_merged_stats_endpoints":false,"has_pci_credit_card_custom_field":true,"current_brand_id":68397,"help_center_restricted":false,"current_brand_active":true,"is_assuming_someone_else":false,"has_assume_csrf_protection":true,"flash_messages":[]};
</script>

  <script src="//static.zdassets.com/hc/assets/moment-f6f8513da6ab17eadada59a1a4edb536.js"></script>
  <script src="//static.zdassets.com/hc/assets/hc_enduser-e51fd6ec33d570dc1435b24b0e10308f.js"></script>
  
</body>
</html>
