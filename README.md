# bootstrap-tab
bootstrap 4 and bootstrap 3 differance billow.

<!--This is Bootstrap 4 -->
<ul class="nav nav-pills mb-3" id="pills-tab" role="tablist">
  <li class="nav-item"><a class="active" id="pills-home-tab" data-toggle="pill" href="#pills-home">Home</a></li>
  <li class="nav-item"><a id="pills-profile-tab" data-toggle="pill" href="#pills-profile" >Profile</a></li>
  <li class="nav-item"><a id="pills-contact-tab" data-toggle="pill" href="#pills-contact" >Contact</a></li>
</ul>

<div class="tab-content">
  <div class="tab-pane fade show active" id="pills-home">...</div>
  <div class="tab-pane fade" id="pills-profile">...</div>
  <div class="tab-pane fade" id="pills-contact">...</div>
</div>


<!--This is Bootstrap 3 -->
 <!-- Nav tabs -->
  <ul class="nav nav-tabs" role="tablist">
    <li class="active"><a href="#home" data-toggle="tab">Home</a></li>
    <li><a href="#profile" data-toggle="tab">Profile</a></li>
    <li ><a href="#messages" data-toggle="tab">Messages</a></li>
    <li ><a href="#settings" data-toggle="tab">Settings</a></li>
  </ul>

  <!-- Tab panes -->
  <div class="tab-content">
    <div class="tab-pane active" id="home">...</div>
    <div class="tab-pane" id="profile">...</div>
    <div class="tab-pane" id="messages">...</div>
    <div class="tab-pane" id="settings">...</div>
  </div>
