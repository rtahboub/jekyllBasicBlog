---
layout: template1
comments: false
---
<br/>

Use the below form and feel free to send a message! :)

<br/>

<div class="panel panel-default shadow1">
      <div class="panel-heading">
        <h4 class="text-primary">Contact</h4>
      </div>
      <div class="panel-body">
            <form id="contactform" method="POST">
                  <div class="form-group">
                        <label for="name" class="control-label">Your name</label>
                        <input id="name" type="text" name="name" class="form-control">
                  </div>
                  <div class="form-group">
                        <label for="email" class="control-label">Your email</label>
                        <input id="email" type="email" name="_replyto" class="form-control">
                  </div>
                  <div class="form-group">
                        <label for="msg" class="control-label">Your message</label>
                        <textarea id="msg" name="message" class="form-control"></textarea>
                  </div>
                
                  <input type="text" name="_gotcha" style="display:none" />
                  <input type="submit" value="Send" class="btn btn-primary">
            </form>
      </div>
</div>
