---
layout: default
title: Centurion Generate
section: custom
permalink: /generate.html
---

<section class="grid-100 alpha hide-desktop">
  <h2>Wait&hellip;hold it&hellip;</h2>
  <p>Unfortunately you cannot create or download custom files on a mobile device.</p>
  <p>Please visit this page on your desktop computer to create your custom Centurion version.</p>
</section>

<section id="generator">

  <section class="grid-75 alpha hide-mobile">
    <p>Build your own custom version of Centurion. Need only the responsive grid, or only a specific jQuery function for your next project.</p>
  </section>
  
  <!--=======================================
      CSS Generate 
  =======================================-->
  <section class="grid-66 hide-mobile">
    <h2 class="generate-header">1. Choose Your CSS components</h2>
    <p><a class="toggle-all">Toggle All</a></p>
    
    <div class="custom-downloads" id="css-downloads">
    
      <article class="generate">
        <div class="grid-33 alpha">
          <label class="checkbox" style="display:none;">
            <input checked="checked" type="checkbox" value="src/css/frameworkComment.css" disabled="disabled"> 
            Comment
          </label>
        
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/grids.css"> 
            Grid
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/alerts.css"> 
            Alerts
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/breadcrumbs.css"> 
            Breadcrumbs
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/buttons.css"> 
            Buttons
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/images.css"> 
            Images
          </label>
    
        </div>
        <div class="grid-33">
    
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/navigation.css"> 
            Navigation
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/panels.css"> 
            Panels
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/pagination.css"> 
            Pagination
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/tabs.css"> 
            Tabs
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/tables.css"> 
            Tables
          </label>
          
        </div>
        <div class="grid-33 omega">
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/tooltips.css"> 
            Tooltips
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/typography.css"> 
            Typography
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/code.css"> 
            Code
          </label>
          
          <label class="checkbox" style="display:none;">
            <input checked="checked" type="checkbox" value="src/css/frameworkCombined.css" disabled="disabled"> 
            Combined
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/css/print.css"> 
            Print
          </label>
          
        </div>
          
        <div class="grid-100 alpha">
          <a class="button small orange" data-bind="css-downloads" id="css-generate">Generate CSS</a>
          <a class="button small blue" id="css-download" download="centurion.3.3.css">Download CSS</a>
        </div>  
        
        <div class="clear"></div>
        <textarea id="generated-css-source">// Generated source</textarea>
        
      </article>
    </div>
    
  </section>

<!--
  <section class="grid-33 hide-mobile">
    <h2 class="generate-header">Need IE7 Support?</h2>
    <p><a class="button small blue" id="ie-download" download="centurion.ie.css">Download IE7 Grid</a></p>
  </section>
-->


  
  <!--=======================================
      jQuery Generate 
  =======================================-->
  <section class="grid-66 alpha hide-mobile">
    <h2 class="generate-header">2. Choose Your jQuery Functions</h2>
    <p><a class="toggle-all">Toggle All</a></p>
    
    <div class="custom-downloads" id="js-downloads">
    
      <article class="generate">
        <div class="grid-50 alpha">
    
    	    <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/js/alerts.js"> 
            Alerts
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/js/navigation.js"> 
            Navigation
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/js/mobileNav.js"> 
            Mobile Navigation
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/js/tables.js"> 
            Tables
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/js/tabs.js"> 
            Tabs
          </label>
        
        </div>
        <div class="grid-50 alpha">
        
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/js/tooltips.js"> 
            Tooltips
          </label>
          
          <label class="checkbox">
            <input checked="checked" type="checkbox" value="src/js/sampleINIT.js"> 
            Default Initialization
          </label>
    
        </div>
      
        <div class="grid-100 alpha">
          <a class="button small orange" data-bind="js-downloads" id="js-generate">Generate JS</a>
          <a class="button small blue" id="js-download" download="centurion.3.3.js">Download JS</a>
        </div>
        
        <div class="clear"></div>
        <textarea id="generated-js-source">// Generated source</textarea>
      </article>
    </div>
  </section>
  
<!--
  <section class="grid-33 hide-mobile">
    <h2 class="generate-header">_____</h2>
    <p><a class="button small blue" id="_____-download" download="_____">_____</a></p>
  </section>
-->
  
  

</section>
