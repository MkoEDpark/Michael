# Michael
NIM PROYEK
%form.form{:autocomplete=>"off"}
  .control  
    %h1
      Sign In
  .control.block-cube.block-input
    %input{:name => "username", :type=>"text", :placeholder=>"Username", }/  
    .bg-top
      .bg-inner
    .bg-right
      .bg-inner
    .bg
      .bg-inner  
  .control.block-cube.block-input
    %input{:name => "password", :type=>"password", :placeholder=>"Password"}/  
    .bg-top
      .bg-inner
    .bg-right
      .bg-inner
    .bg
      .bg-inner  
      
  %button.btn.block-cube.block-cube-hover{:type=>"button"}
    .bg-top
      .bg-inner
    .bg-right
      .bg-inner
    .bg
      .bg-inner
    -# .bg2
    .text
      Log In
  .credits
    %a{:href => "https://codepen.io/marko-zub/", :target=>'_blank'}
      My other codepens    
