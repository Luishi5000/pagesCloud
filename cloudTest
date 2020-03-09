<!doctype html>
<html>
<head>
 <meta charset="utf-8">
 <title></title>
 <meta name="description" content="">
 <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://pub.s7.exacttarget.com/fkbkh5kkp2k">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.0/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <script src="https://pub.s7.exacttarget.com/s0mun5313la"></script>
  <script src="https://pub.s7.exacttarget.com/gonhzdxdbpu"></script>

  <style>
   html, body {
    height: 100%;
   }
   input:disabled {
     background: #dddddd;
   }
   .modified {
     background: green !important;
   }
   .commented {
     background: rgb(85, 255, 158) !important;
   }
   .newcomment {
     color: rgb(219, 236, 83);
   }
   .notify {
     background: rgb(227, 157, 39)
   }
   .modifiedExt {
     color: rgb(36, 255, 0) !important;
   }
   .marked {
     background: yellow;
   }
   .unfilled {
     color: rgb(131, 131, 131);
   }
   .loggedIn {
     color: rgb(19, 235, 0);
   }
   .selectedHighlight {
     background: rgb(21, 173, 4);
   }
   .uiTable {
     margin: auto;
   }
   .spanBlock {
     display: inline-block;
   }

   td:focus {
     background: #b6e6f7;
   }
   #rootTableStore {
     max-height: 240px;
     overflow-y: auto;
     overflow-x: hidden;
     background: #ffc2fd;
   }
   #rootTableStore td {
     padding-right: 10px;
   }
   #rootTableStore tr:hover {
     background-color: rgb(174, 246, 146);
   }
   #campaignTableStore {
     background: rgb(82, 184, 107);
   }
   #propTableStore {
     background: rgb(231, 187, 33);
     overflow: auto;
   }
   #campaignFrame {
     background: rgb(147, 216, 242);
     visibility: hidden;
     display: none;
   }
   #topNavBar {
     width: 100%;
     height: 40px;
     background: #d96feb;
   }
   #containerLeft {
     width: 100%;
     height: 100%;
     background: rgb(80, 60, 221);
     display: flex;
     flex-direction: column;
     spellcheck: "false";
     background: url("https://image.email.greatwolfmail.com/lib/fe8f13727c65027976/m/3/wolf_bg1.jpg");
     background-size: cover;
   }
   #containerRight {
     width: 0%;
     display: none;
     background: rgb(116, 246, 179);
     overflow: auto;
   }
   #mainContainer {
     display: flex;
   }
   #historyPop {
     background: rgb(77, 77, 77);
     color: rgb(214, 214, 214);
     position: absolute;
     left: 0;
     top: 0;
     visibility: hidden;
   }

   #dropdownPop {
     background: rgb(77, 77, 77);
     color: rgb(214, 214, 214);
     position: absolute;
     left: 0;
     top: 0;
     visibility: hidden;
     cursor: pointer;
   }

   #descriptionPop {
     background: rgb(77, 77, 77);
     color: rgb(214, 214, 214);
     position: absolute;
     left: 0;
     top: 0;
     visibility: hidden;
     max-width: 400px;
   }

   #historyPop .spanItem {
     display:none;
   }

   #historyPop:hover .spanItem {
     display:inline;
     color:rgb(252, 184, 95);
   }

   #hiddenInput {
     position: absolute;
     opacity: 0;
   }

   #mainiFrame {
     position: relative;
     height: 100%;
     width: 100%;
   }

   #rightFrameNav {
     text-align: right;
   }

   #newrow_0 {
     background: rgb(82, 178, 242);
   }

   #loginBox {
     margin: auto;
     color: white;
   }

   #loginBox input {
     color: rgb(56, 56, 56);
   }

   .focusedTgt {
     background: rgb(190, 187, 143);
   }


   .visibleToggle {
     visibility: visible !important;
   }
   .displayToggle {
     display: block !important;
   }
   .changedNew {
     background: #dbffd6;
   }

   .dropdownSel:hover {
     font-weight: bold;
   }

   .multidropsel:hover {
     font-weight: bold;
   }

   .multidropsel {
     user-select: none; /* supported by Chrome and Opera */
     -webkit-user-select: none; /* Safari */
     -khtml-user-select: none; /* Konqueror HTML */
     -moz-user-select: none; /* Firefox */
     -ms-user-select: none; /* Internet Explorer/Edge */
   }

   span.multiSelected {
     font-weight: bold !important;
     color: rgb(246, 255, 70) !important;
   }

   input.multiSelected {
     color: rgb(23, 11, 0) !important;
   }



  </style>

</head>
<body>
  <div id="topNavBar">
    <div class="navMenu">
    </div>
    <div class="notifications"></div>
  </div>

  <div id="mainContainer">
    <div id="containerLeft" spellcheck="false">
      <div id="rootTableStore"></div>
      <div id="campaignFrame">
        <div id="editCampaignNameDiv"><span class="spanBlock" id="editCampaignName" contenteditable="true"></span></div>
        <div id="editCampaignDatesDiv"><span class="spanBlock dateSelect" id="editCampaignDateStart" contenteditable="true"></span><br /><span class="spanBlock dateSelect" id="editCampaignDateEnd" contenteditable="true"></span></div>
        <div id="editCampaignDescriptionDiv"><span class="spanBlock" id="editCampaignDescription" contenteditable="true"></span></div>
        <div id="editCampaignInfo"><span class="spanBlock" id="editCampaignID" contenteditable="true"></span><br /><span class="spanBlock" id="editCampaignDE" contenteditable="true"></span></div>
        <div id="editCampaignOptions"></div>
        <div id="editCampaignSave"><span class="spanBlock hidden" data-name="propertyFieldOptions" data-detarget="rootCampaign" id="editPropertyFieldOptions" contenteditable="true"><span class="spanBlock hidden" data-name="campaignFieldOptions" data-detarget="rootCampaign" id="editCampaignFieldOptions" contenteditable="true"></div>
      </div>
      <div id="campaignTableStore"></div>
      <div id="propTableStore"></div>
    </div>
    <div id="containerRight">
      <div id="previewPane">
        <div id="rightFrameNav">
          <span id="frameDesktopIco">desktop</span> <span id="frameMobileIco">mobile</span> <span id="frameCloseIcon">close</span>
        </div>
        <iframe id="mainiFrame"></iframe>
      </div>
      <div id="historyPane">
      </div>
    </div>
  </div>
  <div id="hiddenDiv">
  </div>

  <div id="notificationFrame"></div>

  <div id="storeSelectedCamp"></div>

  <div id="storePg" style="display: none;"></div>

  <div id="storeInput"></div>

  <div style="align-content: center; text-align:center;">

  <div id="segmentFrame"></div>
  <div id="hidehereok">
    <div id="historyPop"></div>
    <div id="dropdownPop"></div>
    <div id="descriptionPop"></div>
  </div>



  input test:<br /><br />




  <div>
  %%[IF @savedshow == 1 THEN]%% SAVED %%[ENDIF]%%
  Status = %%= v(@StatMessage) =%% -- %%= v(@ErrorCode) =%%

  </div><br />


  <div id="rootTableStore"></div>
  <div id="campaignTableStore"></div>
  <div id="propTableStore"></div>
  </div>
  <div id="hiddenInput"><input id="datePickInput" class="datepicker" size="2" data-originid=""></input></div>
</body>
  <script>

  //Order of fields that will populate the table with proper names
  var globalRootFieldsOrder;
  var globalCampaignFieldsOrder;
  var globalSelectedCampaign;
  var globalChangeSet;
  var globalFocusedElement;
  var globalShiftPressed;
  var globalCalendarSelectedTrig;
  var globalDropdownHover;
  var globalHistoryHover;
  var globalPaneActive = 0;
  var rootArray,selectedRoot,campaignArray,propertyArray,rootTable,campaignTable,propertyTable,returnArray;
  var deIdentifier = "detgt__";
  var globalSelectedChangeID = "";
  var globalPropertiesList;
  var globalDropdownVisible = 0;
  var globalHistoryVisible = 0;
  var globalDefaultCommentText = "type comment...";
  var globalLoggedInUser;
  var globalPulledUser;
  var globalPasswordToken;

  $( document ).ready(function() {
    initInputs();
    calcSizes();
    initLogin();
    if (clearUndefined(globalPulledUser) != "") {
      callCampaignData();
    };
  });

  $(window).resize(function(){
   calcSizes();
  });

  //initialize datepicker
  $('.datepicker').datepicker();

  $.urlParam = function(name){
      var results = new RegExp('[\?&]' + name + '=([^&#]*)').exec(window.location.href);
      if (results==null){
         return null;
      } else {
         return results[1] || 0;
      }
  }

  $(document).click(function(event) {
  var etarget = $(event.target);
  var eclosest = etarget.closest('#dropdownPop');
  var hclosest = etarget.closest('#historyPop');
  if((eclosest.length == 0) && (globalDropdownVisible == 1)) {
    $("#dropdownPop").removeClass("visibleToggle");
    globalDropdownVisible = 0;
  };
  if((hclosest.length == 0) && (globalHistoryVisible == 1)) {
    closeHistory();
  };
});

  $('.navMenu').on('click', '.genCampaign', function(e){
    $(this).blur();
    e.preventDefault();
    populateCampaign();
  });

  $('.navMenu').on('click', '.editCampaign', function(e){
    $(this).blur();
    e.preventDefault();

    //rootCampaignID|rootCampaignName|rootCampaignDesc|rootCampaignTgtDE|rootStatus|rootDateStart|rootDateEnd|rootvHTML|rootCampaignID
    populateCampaign(selectedRoot[0][0],selectedRoot[0][1],selectedRoot[0][2],selectedRoot[0][3],selectedRoot[0][4],selectedRoot[0][5],selectedRoot[0][6],selectedRoot[0][7],selectedRoot[0][8]);
  });

  $('.navMenu').on('click', '.genSegment', function(e){
    $(this).blur();
    e.preventDefault();
    newSegment(globalCampaignFieldsOrder);
  });

  $('.navMenu').on('click', '.process', function(e){
    $(this).blur();
    e.preventDefault();
    callCampaignData();
  });

  $('#containerLeft').on('click', '#login', function(e){
    var username = $('#usernameLogin').val();
    var password = $('#passwordLogin').val();
    callCampaignData('','userLogin|' + username + '|' + password);
    //setCookie('timbertoken',username + '|' + password,31);
  });

  $('.navMenu').on('click', '#logout', function(e){
    eraseCookie('timbertoken');
    $('#loginStatus').removeClass('loggedIn');
    $("#rootTableStore").empty();
    $("#campaignTableStore").empty();
    $("#propTableStore").empty();
    initLogin();
    //setCookie('timbertoken',username + '|' + password,31);
  });


  $('#containerLeft').on('click', '#createPassword', function(e){
    var username = $('#usernameLogin').val();
    var password = $('#passwordLogin').val();
    callCampaignData('','userCreatePass' + globalPasswordToken + '|' + username + '|' + password);
  });

  $('#containerLeft').on('click', '#forgot', function(e){
    var username = $('#usernameLogin').val();
    if (clearUndefined(username) != ""){
      callCampaignData('','forgotUserPass' + '|' + username + '|reset' );
    } else {
      $('#usernameLogin').addClass("notify");
    };
  });




  $('.navMenu').on('click', '.submitCampaign', function(e){
    $(this).blur();
    e.preventDefault();
    var fieldInput = $.trim(document.getElementById("storeInput").innerHTML);
    callCampaignData(clearUndefined(globalSelectedCampaign),fieldInput,true);
  });

  $('.navMenu').on('click', '.activityLog', function(e){
    $("#previewPane").addClass("hidden");
    $("#historyPane").removeClass("hidden");
    $('#containerRight').css('min-width', '600px');
    $('#containerRight').css('display', 'block');
    popActivityLog();
    globalPaneActive = 2;
  });


  $('#rootTableStore').on('click', '.root', function(e){
    var getRootDE = $(this).find(".rootCampaignTgtDE").html();
    $("#storeSelectedCamp").empty();
    $("#storeSelectedCamp").append(getRootDE);
    callCampaignData(getRootDE);
  });

  $('#rootTableStore').on("mouseenter",".root", function(e) {
    var $target = $(e.currentTarget);
     $('#descriptionPop').html($target.find(".rootCampaignDesc").html());
     $('#descriptionPop').addClass("visibleToggle");
     var popPosition = $target.offset()
     popPosition.top += $target.height();
     popPosition.left += $target.width();
     $('#descriptionPop').css(popPosition);
  });

  $('#rootTableStore').on("mouseleave",".root", function(e) {
     $('#descriptionPop').removeClass("visibleToggle");
  });

  $('#dropdownPop').mouseenter(function() {
    globalDropdownHover = 1;
  });

  $('#dropdownPop').mouseleave(function() {
    globalDropdownHover = 0;
  });

  $('#historyPop').mouseenter(function() {
    globalHistoryHover = 1;
    $('.commentIcon').addClass('hidden');
    $('.comment').removeClass('hidden');
  });

  $('#historyPop').mouseleave(function() {
    globalHistoryHover = 0;
    if (document.activeElement.className.indexOf("comment") == -1){
      $('.commentIcon').removeClass('hidden');
      $('.comment').addClass('hidden');
    };
  });


  $('#dropdownPop').on('click', '.dropdownSel', function(e){
    var string = $(this).html();
    $("#dropdownPop").removeClass("visibleToggle");
    globalDropdownVisible = 0;
    var target = globalFocusedElement;
    $(target).html(string);
    $(target).addClass('modified');
    $(target).blur();
  });

  $('#dropdownPop').on('click', '.multidropsel', function(e){
    $(this).toggleClass('multiSelected');
  });

  $('#dropdownPop').on('click', '.multidropselSave', function(e){
    var exttgt = $(this).data("exttgt");
    var buildString = "";
    $("#dropdownPop").removeClass("visibleToggle");
    globalDropdownVisible = 0;
    var target = "#" + $(this).data("exttgt");
    $(".multiSelected").each(function(){
      var tag = $(this).prop("tagName");
      if (tag == "INPUT"){
        buildString += $(this).val() + ",";
      } else {
        buildString += $(this).html() + ",";
      };
    });

    var tgtTag = $(target).prop("tagName");
    if (tgtTag == "INPUT"){
      $(target).val(buildString);
    } else {
      $(target).html(buildString);
    }

    $(target).addClass('modified');
    $(globalFocusedElement).addClass('modifiedExt');
    collectText();
    populateHTMLtest();
    $(target).blur();
  });

  $('#dropdownPop').on('click', '.multidropselCancel', function(e){
    $("#dropdownPop").removeClass("visibleToggle");
    globalDropdownVisible = 0;
    $(target).blur();
  });

  $('#dropdownPop').on('click', '#dropdown_Create_HTML_Test', function(e){
    var targetID = "#" + $(this).data("tgtid");
    $(targetID).append(",");
    $(targetID).addClass("notify");
    /*
    $(target).attr('name',$(this).data("tgtcampaign"));
    $(target).data('detarget','createHTMLTest');
    $(target).val($(this).data("tgtsegment"));
    $(target).addClass('modified');
    $("#dropdownPop").removeClass("visibleToggle");
    */
    collectText();
    populateHTMLtest();
    $("#dropdownPop").removeClass("visibleToggle");
    globalDropdownVisible = 0;
  });

  $('#dropdownPop').on('click', '#dropdown_Create_Segment_Test', function(e){
    var target = "." + $(this).data("exttgt");
    $(target).attr('name',$(this).data("tgtcampaign"));
    $(target).data('detarget','createSegmentTest');
    $(target).val($(this).data("tgtsegment"));
    $(target).addClass('modified');
    $("#dropdownPop").removeClass("visibleToggle");
    globalDropdownVisible = 0;
    collectText();
    $(target).blur();
  });


  $('#containerLeft').on('click', '', function(e) {
    if ($(event.target).attr("contentEditable") == "true") {
      selectText(event.target.id);
      globalFocusedElement = "#" + event.target.id;
      if ($(event.target).hasClass("dateSelect")) {
        var position = $(globalFocusedElement).offset();
        $("#hiddenInput").css(position);
        $("#hiddenInput").css("visibility","visible")
        $("#datePickInput").attr("data-originid",globalFocusedElement);
        if (isDate($(event.target).html())) {
          $("#datePickInput").datepicker('setDate', new Date($(event.target).html()));
          $('#datePickInput').datepicker('update');
        } else {
          $("#datePickInput").datepicker('setDate', new Date());
          $('#datePickInput').datepicker('update');
        }
        globalCalendarSelectedTrig = 0;
        $(event.target).addClass("focusedTgt");
        $("#datePickInput").focus();
      }

      if (e.shiftKey) {
        $(event.target).toggleClass("marked");
        globalShiftPressed = 1;
      }
      getChanged = clearUndefined($(event.target).data("changed"));
      //if (clearUndefined(getChanged) != "") {
        popHistory(getChanged);
      //}
    };

    if ($(event.target).hasClass("dropdown")) {
      globalFocusedElement = "#" + event.target.id;
      getOptions = $(event.target).data("options");
      if (clearUndefined(getOptions) != "") {
        popDropdown(getOptions,$(event.target).width());
      }
    };

    if ($(event.target).hasClass("multidropdown")) {
      globalFocusedElement = "#" + event.target.id;
      getOptions = $(event.target).data("options");
      if (clearUndefined(getOptions) != "") {
        popDropdown(getOptions,$(event.target).width(),true,$(globalFocusedElement).data("exttgt"));
      };
    };

    if ($(event.target).hasClass("dropdownTargeted")) {
      globalFocusedElement = "#" + event.target.id;
      getOptions = $(event.target).data("options");
      if (clearUndefined(getOptions) != "") {
        popDropdown(getOptions,$(event.target).width(),"targeted",$(globalFocusedElement).data("exttgt"));
      };
    };

    if ($(event.target).hasClass("dropdownfield")) {
      globalFocusedElement = "#" + event.target.closest("td").id;
      var getContent = $(globalFocusedElement).html().replace(/<.+?>/g,"");
      if (clearUndefined(getContent) != "") {
        popDropdown(getContent,$(event.target).width(),"fieldset", event.target.getAttribute("data-exttgt"));
      };
    };

    if ($(event.target).hasClass("loginInput")) {
      globalFocusedElement = "#" + event.target.id;
    };
  });

  $('#containerLeft').on('click', '.htmlPreview', function(e) {
    var tgtlink = $(this).data("tgtlink");
    $("#previewPane").removeClass("hidden");
    $("#mainiFrame").attr("src",tgtlink);
    $('#containerRight').css('min-width', '600px');
    $('#containerRight').css('display', 'block');
    globalPaneActive = 1;
  });

  $('#containerRight').on('click', '#frameDesktopIco', function(e) {
    $('#containerRight').css('min-width', '600px');
  });

  $('#containerRight').on('click', '#frameMobileIco', function(e) {
    $('#containerRight').css('min-width', '480px');
  });

  $('#containerRight').on('click', '#frameCloseIcon', function(e) {
    $('#containerRight').css('min-width', '0px');
    $('#containerRight').css('display', 'none');
    $("#containerRight").width(0);
    $("containerLeft").width($(document).width());
    globalPaneActive = 0;
  });




  $("#datePickInput").datepicker().on("show", function (e) {
    $('div tbody').on('click', 'tr > .day', function () {
      globalCalendarSelectedTrig = 1;
    })
  });


  function isDate(val) {
    var d = new Date(val);
    return !isNaN(d.valueOf());
  };



  $('#datePickInput').datepicker().on('hide', function(e) {
      $(globalFocusedElement).removeClass("focusedTgt");

      if ($(this).val()) {
        if (globalCalendarSelectedTrig == 1) {
          var target = globalFocusedElement;
          $(target).html($(this).val());
          $("#hiddenInput").css("visibility","hidden")
          $(target).addClass('modified');
          if (globalShiftPressed == 2) {
            globalShiftPressed = 3;
          }
          /*setTimeout(function() {
            $(target).focus();
          }, 0); auto select text after date*/
        }
      }
  });

  /*$('#datePickInput').on( 'focusout', function( e ) {
    var target = $("#datePickInput").data("originid");
    $(target).html($(this).val());
    $(target).focus();
  });*/




  $('#containerLeft').on( 'keyup', function( e ) {
    if( e.which == 9 ) {
      if ($(document.activeElement).attr("contentEditable") == "true") {
        selectText(document.activeElement.id);
      };
    };
  });

  $('#containerLeft').on( 'focusout', function( e ) {
    if (globalHistoryHover == 0) {
      closeHistory();
    };
    if (globalDropdownHover == 0) {
      $("#dropdownPop").removeClass("visibleToggle");
      globalDropdownVisible = 0;
    }
    if (globalShiftPressed == 2) {
      $(".marked").each(function(){
          $(this).removeClass("marked");
      });
      globalShiftPressed = 0;
    };
  });

  function initLogin() {
    $('.navMenu').empty();
    $('.notifications').empty();
    $('#loginBox').remove();
    var cookie = getCookie("timbertoken");
    if (cookie) {
     //document.getElementById("testCookieBox").innerHTML = cookie;
     globalPulledUser = cookie;
     $('.navMenu').append('<a href="#" class="process" style="text-decoration: none; color: #4B06DC; font-size: 12px; padding-top: 4px; padding-left: 6px;"><span class="glyphicon glyphicon-refresh"></span></a>');
     $('.navMenu').append('<a href="#" class="genCampaign" style="text-decoration: none; color: #4B06DC; font-size: 12px; padding-top: 4px; padding-left: 6px;"><span class="glyphicon glyphicon-certificate"></span> Generate Campaign</a>');
     $('.navMenu').append('<a href="#" class="editCampaign" style="text-decoration: none; color: #4B06DC; font-size: 12px; padding-top: 4px; padding-left: 6px;"><span class="glyphicon glyphicon-certificate"></span> Edit Campaign</a>');
     $('.navMenu').append('<a href="#" class="submitCampaign" style="text-decoration: none; color: #4B06DC; font-size: 12px; padding-top: 4px; padding-left: 6px;"><span class="glyphicon glyphicon-certificate"></span> SubmitCamp</a>');
     $('.navMenu').append('<a href="#" class="activityLog" style="text-decoration: none; color: #4B06DC; font-size: 12px; padding-top: 4px; padding-left: 6px;"><span class="glyphicon glyphicon-certificate"></span> Acitivty Log</a>');
     $('.notifications').append(cookie);
     $('.navMenu').append('<span id="loginStatus" class="glyphicon glyphicon-thumbs-up"></span>');
     $('#loginStatus').addClass('loggedIn');
     $('.navMenu').append('<span id="logout" class="glyphicon glyphicon-remove-sign"></span>');
   } else {
     $('#containerLeft').append('<div id="loginBox"></div>');
     $('#loginBox').append('Username: <input id="usernameLogin" class="loginInput"></input>');
     globalPasswordToken = $.urlParam('pwtoken');
     if ((clearUndefined(globalPasswordToken) != "") && (globalPasswordToken != null)) {
       $('#loginBox').append(' Create New Password: <input id="passwordLogin" class="loginInput"></input> ');
       $('#loginBox').append('<span id="createPassword" class="glyphicon glyphicon-arrow-right"></span>');
     } else {
       $('#loginBox').append(' Password: <input id="passwordLogin" class="loginInput"></input> ');
       $('#loginBox').append('<span id="login" class="loginArrow glyphicon glyphicon-arrow-right"></span>');
       $('#loginBox').append('<span id="forgot" class="glyphicon glyphicon-question-sign"></span>');
     };
    };
  };

  function selectText(node) {
    node = document.getElementById(node);

    if (document.body.createTextRange) {
        const range = document.body.createTextRange();
        range.moveToElementText(node);
        range.select();
    } else if (window.getSelection) {
        const selection = window.getSelection();
        const range = document.createRange();
        range.selectNodeContents(node);
        selection.removeAllRanges();
        selection.addRange(range);
    } else {
        console.warn("Could not select text in node: Unsupported browser.");
    };
  };

  function popHistory(getChangedArr) {
    $("#historyPop").empty();
    $("#historyPop").addClass("visibleToggle");
    var position = $(globalFocusedElement).offset();
    position.top += $(globalFocusedElement).height();
    position.left += $(globalFocusedElement).width();
    $("#historyPop").css(position);
    if (clearUndefined(getChangedArr) != "") {
      var checkArr = csvToArray(getChangedArr);
      var checkComment = 1; //skip the first value
      if (globalChangeSet[checkArr[0][0]][2] == "comment"){
        checkComment = 0;
      };
      for (i = checkComment; i < checkArr.length - 1; i++) {
        $("#historyPop").append(globalChangeSet[checkArr[i][0]][3] + "<span class='hisUser spanItem'>" + globalChangeSet[checkArr[i][0]][1] + "</span>" + "<span class='hisTime spanItem'>" + globalChangeSet[checkArr[i][0]][0] + "</span>" + "<br />"); //append the stored check array number within the larger global change set array
      };
      var commentString = clearUndefined($(globalFocusedElement).attr("data-comment"));
      if (commentString == "") {
        commentString = globalDefaultCommentText;
        $("#historyPop").prepend('<span class="glyphicon glyphicon-comment commentIcon"></span><br />');
        $("#historyPop").prepend("<span id='commentid' class='comment hidden' contenteditable='true'>" + commentString + "</span>");
      } else {
        $("#historyPop").prepend("<span id='commentid' class='comment newcomment' contenteditable='true'>" + commentString + "</span><br />");
      };

    } else {
      var commentString = clearUndefined($(globalFocusedElement).attr("data-comment"));
      if (commentString == "") {
        commentString = globalDefaultCommentText;
        $("#historyPop").prepend('<span class="glyphicon glyphicon-comment commentIcon"></span><br />');
        $("#historyPop").prepend("<span id='commentid' class='comment hidden' contenteditable='true'>" + commentString + "</span>");
      } else {
        $("#historyPop").prepend("<span id='commentid' class='comment' contenteditable='true'>" + commentString + "</span>");
      };
    };

    setTimeout(function () {
      globalHistoryVisible = 1;
    },100);
  };

  function closeHistory() {
    if (document.activeElement.id != globalFocusedElement.replace("#","")) {
      $("#historyPop").removeClass("visibleToggle");
      globalHistoryVisible = 0;
      var comment = $(".comment").text();
      if ((comment != globalDefaultCommentText) && (comment.trim() != "")){
        $(globalFocusedElement).attr("data-comment",comment);
        $(globalFocusedElement).addClass("commented");
      } else {
        $(globalFocusedElement).attr("data-comment","");
        $(globalFocusedElement).removeClass("commented");
      };
      collectText();
      $(".comment").text("");
    };
  };

  $('#historyPop').on( 'click', function( e ) {
    selectText(event.target.id);
  });

  function popDropdown(getOptions,getWidth,multiselect,externalTarget) {
    $("#dropdownPop").empty();
    $("#dropdownPop").addClass("visibleToggle");
    globalDropdownVisible = 0; //set to 0 in case a double click has stuck it to on within the 100ms window
    var position = $(globalFocusedElement).offset();
    position.top += $(globalFocusedElement).height();
    $("#dropdownPop").css(position);
    $("#dropdownPop").css('min-width', getWidth);
    var getValues;
    var workingTarget = "." + externalTarget; //If value already present in target input, use that instead to retain existing picks
    var workingExtValue = $(workingTarget).val();
    var checkArr = csvToArray2(getOptions);
    if (multiselect == true) {
      for (i = 0; i < checkArr.length; i++) {
        var addMultiClass = "";
        var workingString = checkArr[i][0];

        //if no input then populate default "s_" variables
        if (workingString.indexOf("s_") == 0) {
          if (clearUndefined(workingExtValue) == "") {
            addMultiClass = " multiSelected";
          };
        };

        //if input, then populate only those with inputs
        if (clearUndefined(workingExtValue) != "") {
          if (workingExtValue.indexOf(workingString.replace("s_","")) > -1) {
            addMultiClass = " multiSelected";
          };
        };

        workingString = workingString.replace("s_","")

        $("#dropdownPop").append("<span class='multidropsel" + addMultiClass + "'>" + workingString + "</span>" + "<br />"); //append the stored check array number within the larger global change set array
      };
      $("#dropdownPop").append("<span class='multidropselSave' data-exttgt=" + externalTarget + ">" + "save" + "</span>");
      $("#dropdownPop").append("<span class='multidropselCancel'>" + " cancel" + "</span>");

    } else if (multiselect == "targeted") {
      for (i = 0; i < checkArr.length; i++) {
        var getSegment = $(globalFocusedElement).closest('.segments').attr('data-tgtproperty');
        var getCampaign = $(globalFocusedElement).closest('.segments').attr('data-detarget');
        var getHTMLtgt = $(globalFocusedElement).closest('.segments').find('.c_vHTML').attr('id');
        $("#dropdownPop").append('<span class="" data-tgtcampaign="' + getCampaign + '" data-tgtsegment="' + getSegment + '" data-tgtid="' + getHTMLtgt + '" data-exttgt="' + externalTarget + '" id="dropdown_' + checkArr[i][0].replace(/ /g,"_") + '">' + checkArr[i][0] + '</span>' + '<br />'); //append the stored check array number within the larger global change set array
      };
    } else if (multiselect == "fieldset") {
      for (i = 0; i < checkArr.length; i++) {
        $("#dropdownPop").append('<input class="multiSelected" value="' + checkArr[i][0] + '"/>' + '<br />');
      };
      $("#dropdownPop").append("<span class='multidropselSave' data-exttgt=" + externalTarget + ">" + "save" + "</span>");
      $("#dropdownPop").append("<span class='multidropselCancel'>" + " cancel" + "</span>");
    } else {
      for (i = 0; i < checkArr.length; i++) {
        $("#dropdownPop").append("<span class='dropdownSel' id='dropdown_" + checkArr[i][0].replace(/ /g,"_") + "'>" + checkArr[i][0] + "</span>" + "<br />"); //append the stored check array number within the larger global change set array
      };
    };

    var posTop = position.top;
    var dropdownHeight = $("#dropdownPop").height();
    var windowHeight = $(window).height();
    if ((posTop + dropdownHeight) > windowHeight) {
      position.top = $(window).height() - $("#dropdownPop").height();
      $("#dropdownPop").css(position);
    };

    setTimeout(function() {
      globalDropdownVisible = 1; //set back to 1 after the 100ms time to enable the pop
    }, 100);

  };

  function popActivityLog() {
    for (i = 0; i < globalChangeSet.length - 1; i++) {
      $("#historyPane").prepend(globalChangeSet[i][3] + "<span class='hisUser spanItem'>" + globalChangeSet[i][1] + "</span>" + "<span class='itemInfo'>" + globalChangeSet[i][0] + "</span>" + "<br />"); //append the stored check array number within the larger global change set array
    };
  };

  //assign listener for collecting inputs
  function initInputs() {
  $(".textField").on('input', function (e) {
    $(this).addClass('modified');
    collectText();
  });

   $('.datepicker').datepicker();
   $('.datepicker').datepicker().on('hide', function(e) {
       if ($(this).val()) {
           $(this).addClass('modified');
           collectText();
       }
   });
 };

  function calcSizes() {
    $('#mainContainer').css('height', $(window).height());
    $('#containerRight').css('height', $('#containerLeft').height());
  };

  $(document).on('keypress', function (e) {
    if(e.which == 13) {
        if ($(globalFocusedElement).hasClass("loginInput")) {
          if ((clearUndefined(globalPasswordToken) != "") && (globalPasswordToken != null)) {
            var username = $('#usernameLogin').val();
            var password = $('#passwordLogin').val();
            callCampaignData('','userCreatePass' + globalPasswordToken + '|' + username + '|' + password);
          } else {
            var username = $('#usernameLogin').val();
            var password = $('#passwordLogin').val();
            callCampaignData('','userLogin' + globalPasswordToken + '|' + username + '|' + password);
          };
        };
        $(':focus').blur();
        if (globalHistoryVisible) {
          closeHistory();
        };
    };
  });

  $(document).on('keyup', function (e) {
    if(e.shiftKey == false) {
        if (globalShiftPressed == 1){
          globalShiftPressed = 2;
        }
    }
  });


  function populatePreviews() {
    $(".properties").each(function() {
      var deTarget = $(this).data("detarget");
      var lookupHTML = "#c_vHTML_" + deTarget.slice(deTarget.indexOf('SEGMENT_') + 8);
      var lookupSegment = "#c_campaignID_" + deTarget.slice(deTarget.indexOf('SEGMENT_') + 8);
      var previewCampaign = $(lookupSegment).html();
      var previewTgt = $(lookupHTML).html();
      var countChar = (previewTgt.match(/,/g) || []).length + 1;
      var previewList = csvToArray2(previewTgt);
      var previewProp = $(this).data("tgtproperty");
      for (c = 0; c < previewList.length; c++) {
        var parsedTarget = previewList[c][0];
        var finalLink = "https://cloud.greatwolf.com/" + parsedTarget + "?campaign=" + previewCampaign + "&propertyCode=" + previewProp;
        if (clearUndefined(parsedTarget) != "") {
          $(this).append($('<td />').html('link').attr('data-tgtLink', finalLink).attr('class', 'htmlPreview'));
        };
      };
    });
  };

  function populateHTMLtest() {
    $(".c_vHTML").each(function() {
      var contents = $(this).html().replace(/<.+?>/g,"");
      var countChar = (contents.match(/,/g) || []).length + 1;
      if (contents.indexOf(",") > 0) {
        $(this).html("<span class='multiHTML_" + countChar + "' style='display: none;'>" + contents + "</span>" + "<span class='glyphicon glyphicon-th-large dropdownfield' data-exttgt='" + $(this).attr('id') + "'></span>");
        $(this).attr('contenteditable','false');
      };
    });
  };

  /*$('body').bind('paste', function() { // catch the paste-event in the DIV
    // get content before paste
    var before = document.getElementById('editor').innerHTML;
    setTimeout(function(){
        // get content after paste by a 100ms delay
        var after = document.getElementById('editor').innerHTML;
        // find the start and end position where the two differ
        var pos1 = -1;
        var pos2 = -1;
        for (var i=0; i<after.length; i++) {
            if (pos1 == -1 && before.substr(i, 1) != after.substr(i, 1)) pos1 = i;
            if (pos2 == -1 && before.substr(before.length-i-1, 1) != after.substr(after.length-i-1, 1)) pos2 = i;
        }
        // the difference = pasted string with HTML:
        var pasted = after.substr(pos1, after.length-pos2-pos1);
        // strip the tags:
        var replace = pasted.replace(/<[^>]+>/g, '');
        // build clean content:
        var replaced = after.substr(0, pos1)+replace+after.substr(pos1+pasted.length);
        // replace the HTML mess with the plain content
        document.getElementById('editor').innerHTML = replaced;
      }, 100);
    });*/

  $('body').bind('paste', function() { // catch the paste-event in the DIV
    setTimeout(function(){
        // get content after paste by a 100ms delay
        $(globalFocusedElement).html($(globalFocusedElement).html().replace(/<.+?>/g,""));
        //$(globalFocusedElement).html($(globalFocusedElement).html().replace("</span>",""));
    }, 100);
  });

  //GENERATE TEXTBOX
  function generateTextbox(name,value,label,deTarget,addClass,disabled,id) {
  disabled = clearUndefined(disabled);
  addClassTxt = "textField " + addClass;
    return label + '<input id="' + id + '" class="' + addClassTxt + '" name="' + name + '" type="text" autocomplete="off" data-detarget="' + deTarget + '" value="'+ value +'" ' + disabled + ' /> '
  };

 //collect all of editable text on entry
function collectText() {
  $("#storeInput").empty();
  var stringHold = "";
  if (globalShiftPressed >= 2) {
    $(".marked").each(function(){
      if ($(this).is(":focus") == false){
        $(this).html($(globalFocusedElement).html())
        $(this).addClass("modified");
      }
      if (globalShiftPressed == 3) {
        $(this).removeClass("marked");
      }
    });
  };

  $(".modified").each(function(){
   var tag = $(this).prop("tagName");

   if (tag == "SPAN") {
     stringHold += $(this).data("detarget");
     stringHold += "|";
     stringHold += $(this).data("name");
     stringHold += "|";
     stringHold += $(this).html();
     stringHold += "¦";
   };

   if (tag == "TD") {
     stringHold += $(this).data("detarget");
     stringHold += "|";
     stringHold += $(this).data("rowtype");
     stringHold += "|";
     stringHold += $(this).data("rowtarget");
     stringHold += "|";
     stringHold += $(this).attr("name");
     stringHold += "|";
     stringHold += $(this).html().replace(/<.+?>/g,""); //replace all instances of extra HTML code such as hidden fields and swapped images
     stringHold += "¦";
   };
  });

  $(".commented").each(function() {
    if (clearUndefined($(this).attr("data-comment")) != "") {
      stringHold += $(this).data("detarget");
      stringHold += "|";
      stringHold += $(this).data("rowtype");
      stringHold += "|";
      stringHold += $(this).data("rowtarget");
      stringHold += "|";
      stringHold += $(this).attr("name");
      stringHold += "|";
      stringHold += $(this).attr("data-comment"); //replace all instances of extra HTML code such as hidden fields and swapped images
      stringHold += "|";
      stringHold += "comment";
      stringHold += "¦";
    };
  });
  $("#storeInput").append(stringHold);
}


  //POPULATE CAMPAIGN VARIABLE TEXT BOXES AND PULL IN INFORMATION IF IT EXISTS
  //Diasabled options are disabled for certain users (ToAdd: classifcations for which users to have disabled content for)
  function populateCampaign(pullRootCampaignID,pullRootCampaignName,pullRootCampaignDesc,pullRootCampaignTgtDE,pullRootStatus,pullRootDateStart,pullRootDateEnd,vHTML){
   pullRootCampaignID = clearUndefined(pullRootCampaignID);
   pullRootCampaignDesc = clearUndefined(pullRootCampaignDesc);
   pullRootCampaignTgtDE = clearUndefined(pullRootCampaignTgtDE);
   pullRootStatus = clearUndefined(pullRootStatus);
   pullRootDateStart = clearUndefined(pullRootDateStart);
   pullRootDateEnd = clearUndefined(pullRootDateEnd);
   //vHTML = clearUndefined(vHTML);


   //If campaign name is present then populate it, otherwise make a new campaign, this is the root field so it cannot be changed once created
   $("#campaignFrame").addClass("visibleToggle");
   $("#campaignFrame").addClass("displayToggle");
   $("#editCampaignOptions").empty();

   if (pullRootCampaignName) {
    //$("#campaignFrame").append(generateTextbox('rootCampaignName',pullRootCampaignName,'Campaign Name','rootEditCampaign','modified','disabled'));
    $("#editCampaignName").html(pullRootCampaignName).attr("data-detarget","rootCampaignName").attr("data-original",pullRootCampaignName).attr("contenteditable","false");
    var pullDefaultTarget = 3;
   } else {
    //$("#campaignFrame").append(generateTextbox('rootCampaignName','','Campaign Name','rootCreateCampaign'));
    $("#editCampaignName").html("Campaign Name").attr("contenteditable","true").attr("data-name","rootCampaignName").attr("data-detarget","rootCampaignName").attr("data-original",pullRootCampaignDesc);
    var pullDefaultTarget = 6;
   };

   if (pullRootCampaignDesc == "") {pullRootCampaignDesc = "Campaign Description..."}
   if (pullRootDateStart == "") {pullRootDateStart = "Start Date"}
   if (pullRootDateEnd == "") {pullRootDateEnd = "End Date"}

   $("#editCampaignDescription").html(pullRootCampaignDesc).attr("data-name","rootCampaignDesc").attr("data-detarget","rootCampaign").attr("data-original",pullRootCampaignDesc);
   $("#editCampaignDateStart").html(pullRootDateStart).attr("data-name","rootDateStart").attr("data-detarget","rootCampaign").attr("data-original",pullRootDateStart);
   $("#editCampaignDateEnd").html(pullRootDateEnd).attr("data-name","rootDateEnd").attr("data-detarget","rootCampaign").attr("data-original",pullRootDateEnd);
   $("#editCampaignID").html(pullRootCampaignID).attr("data-name","campaignSystemID").attr("data-detarget","rootCampaign").attr("data-original",pullRootCampaignID);
   $("#editCampaignDE").html(pullRootCampaignTgtDE).attr("data-name","campaignSystemDE").attr("data-detarget","rootCampaign").attr("data-original",pullRootCampaignTgtDE);

   var optionsString = "";



   for (i = 0; i < globalCampaignFieldsOrder.length; i++) {
     if (globalCampaignFieldsOrder[i][pullDefaultTarget] == "true"){
       optionsString = optionsString + globalCampaignFieldsOrder[i][0].replace("c_","s_") + ",";
     } else {
       optionsString = optionsString + globalCampaignFieldsOrder[i][0].replace("c_","") + ",";
     };
   };

   $("#editCampaignOptions").append('<span id="campaignFieldOptionsIcon" class="glyphicon glyphicon-edit multidropdown" data-exttgt="editCampaignFieldOptions" data-options="' + optionsString + '"></span>');

   var optionsString = "";

   for (i = 0; i < globalPropertyFieldsOrder.length; i++) {
     if (globalPropertyFieldsOrder[i][pullDefaultTarget] == "true"){
       optionsString = optionsString + globalPropertyFieldsOrder[i][0].replace("p_","s_") + ",";
     } else {
       optionsString = optionsString + globalPropertyFieldsOrder[i][0].replace("p_","") + ",";
     };
   };

   $("#editCampaignOptions").append('<span id="propertyFieldOptionsIcon" class="glyphicon glyphicon-edit multidropdown" data-exttgt="editPropertyFieldOptions" data-options="' + optionsString + '"></span>');

   //initialize input capture and datepicker on dates
   initInputs();
 };

  //POPULATE CAMPAIGN VARIABLE TEXT BOXES AND PULL IN INFORMATION IF IT EXISTS
  //Diasabled options are disabled for certain users (ToAdd: classifcations for which users to have disabled content for)
  function newSegment(fieldsArray){

    if (typeof campaignArray !== "undefined") {
      arrayToTable('new',fieldsArray,'', {
      thead: true,
      attrs: {class: 'table'}
    },".campaignTable")
      //$('#campaignTableStore').append(campaignTable);
    }

    var optionsString = "";

    for (i = 0; i < globalPropertiesList.length - 1; i++) {
      optionsString = optionsString + "s_" + globalPropertiesList[i][1] + ",";
    };

    $("#options_new").append('<span id="propertySelection" class="glyphicon glyphicon-home multidropdown" data-exttgt="propertyOptions" data-options="' + optionsString + '"></span>');
    $("#options_new").append(generateTextbox('propertyOptions','','','createNewCampaign','propertyOptions hidden','','propertyOptions'));

   //initialize input capture and datepicker on dates
   initInputs();
  }



  //SET UNDEFINED VARIABLES TO EMPTY STRING SO THEY DON'T APPEAR TO USER
  function clearUndefined(value){
   return (typeof (value) !== 'undefined' ? value : '');
  }

 function csvToArray (csv) {
  rows = csv.split("¦");

  return rows.map(function (row) {
   return row.split("|");
  });
 };

 function csvToArray2 (csv) {
  rows = csv.split(",");

  return rows.map(function (row) {
   return row.split("|");
  });
 };

 function processChangeSet (changeSet) {
    for (c = 0; c < changeSet.length; c++){
     var tagItem = changeSet[c][5] //go through and grab the tag variable and assign it
     if (clearUndefined(tagItem) != "") {
       //try both with and without last de
       var tagItemConcat = "#" + changeSet[c][7].substring(0,1) + "_" + tagItem + "_" + changeSet[c][6];
       var getChanged = clearUndefined($(tagItemConcat).attr("data-changed"));
       if (getChanged == ""){
         var tagItemConcat2 = "";
         tagItemConcat2 = "#" + changeSet[c][7].substring(0,1) + "_" + tagItem + "_" + changeSet[c][6] + "_" + changeSet[c][4];
         var getChanged = clearUndefined($(tagItemConcat2).attr("data-changed"));
         if ($(tagItemConcat2).length != 0) {
           tagItemConcat = tagItemConcat2; //if the matched element exists then make that the new target
         };
       };
       $(tagItemConcat).attr("data-changed",c + "¦" + getChanged);
       if (changeSet[c][8] == globalSelectedChangeID) {
         $(tagItemConcat).addClass("changedNew");
       };
     };
   };
 };

 function populateOptions() {
   var idCounter = 0;
   $(".optionsegments").each(function() {
     //var tgtSegment = $(this).data("tgtSegment");
     $(this).append('<span id="' + "optionsButton_" + idCounter + '" class="createTest dropdownTargeted glyphicon glyphicon-option-horizontal" data-exttgt="inputCreateTest" data-options="Create HTML Test,Create Segment Test"></span>');
     idCounter += 1;
   });
   $("#hiddenDiv").empty();
   $("#hiddenDiv").append(generateTextbox('','','','','inputCreateTest hidd',''));
 };

 window.onload = function() {

 };

 function callCampaignData(selectedCampaign,fieldInput,updateUI){
  var userenc = encodeURIComponent(clearUndefined(globalPulledUser));
  $("#storePg").load("https://cloud.greatwolf.com/processInputsFullScope?campaign=" + clearUndefined(selectedCampaign) + "&input=" + encodeURI(clearUndefined(fieldInput)) + "&changeID=" + clearUndefined(globalSelectedChangeID) + "&username=" + userenc + " div#resultOut",
     function () {

  var campaignFields = "";
  var propertyFields = "";
  var propertiesList = "";
  var changeSet = "";
  var userLogin = "";

  var datais = $.trim(document.getElementById("resultOut").innerHTML);
  var datalk = datais.replace(/&amp;/g, "&")
  var array0 = datalk.split('^')
  var array1 = array0[0] //response
  var array2 = array0[1] //root
  var array3 = array0[2] //root fields
  var array4 = array0[3] //root select
  var array5 = array0[4] //campaign select
  var array6 = array0[5] //campaign fields
  var array7 = array0[6] //property select
  var array8 = array0[7] //property fields
  var array9 = array0[8] //change set
  var array10 = array0[9] //change set
  var array11 = array0[10] //change set

  if (typeof array1 !== "undefined") {returnArray = csvToArray(array1);}
  if (typeof array2 !== "undefined") {rootArray = csvToArray(array2);} //parse to individual elements for main array
  if (typeof array3 !== "undefined") {rootFields = csvToArray(array3);}
  if (typeof array4 !== "undefined") {selectedRoot = csvToArray(array4);}
  if (typeof array5 !== "undefined") {campaignArray = csvToArray(array5);}
  if (typeof array6 !== "undefined") {campaignFields = csvToArray(array6);}
  if (typeof array7 !== "undefined") {propertyArray = csvToArray(array7);}
  if (typeof array8 !== "undefined") {propertyFields = csvToArray(array8);}
  if (typeof array9 !== "undefined") {changeSet = csvToArray(array9);}
  if (typeof array10 !== "undefined") {propertiesList = csvToArray(array10);}
  if (typeof array11 !== "undefined") {userLogin = csvToArray(array11);}

  globalSelectedCampaign = clearUndefined(returnArray[0][0]);
  globalSelectedChangeID = clearUndefined(returnArray[0][1]);
  globalCampaignFieldsOrder = campaignFields;
  globalPropertyFieldsOrder = propertyFields;
  globalPropertiesList = propertiesList;
  globalChangeSet = changeSet;

  $("#rootTableStore").empty();
  $("#campaignTableStore").empty();
  $("#propTableStore").empty();

  //check arrays
  if (typeof rootArray !== "undefined") {
    rootTable = arrayToTable(rootArray,rootFields,'root', {
    thead: false,
    attrs: {class: 'rootTable uiTable'}
    })
    $('#rootTableStore').append(rootTable);
  };

  if (typeof campaignArray !== "undefined") {
    campaignTable = arrayToTable(campaignArray,campaignFields,'segments', {
    thead: true,
    attrs: {class: 'campaignTable uiTable'}
    })
    $('#campaignTableStore').append(campaignTable);
    populateOptions();
  };

  if (typeof propertyArray !== "undefined") {
    propertyTable = arrayToTable(propertyArray,propertyFields,'properties', {
    thead: true,
    attrs: {class: 'propertyTable uiTable'}
  },'',1)
    $('#propTableStore').append(propertyTable);
  };

  populatePreviews();
  populateHTMLtest();


  $("#notificationFrame").empty();
  $('#notificationFrame').append(returnArray[0] + " " + returnArray[1]);

  if (typeof changeSet !== "undefined"){
    processChangeSet(changeSet);
  };

  if (updateUI == true) {
    populateCampaign(selectedRoot[0][0],selectedRoot[0][1],selectedRoot[0][2],selectedRoot[0][3],selectedRoot[0][4],selectedRoot[0][5],selectedRoot[0][6],selectedRoot[0][7]);
  };

  if (clearUndefined(globalSelectedCampaign) != "") {
    $(".navMenu").append($(' <a href="#" class="genSegment" style="text-decoration: none; color: #4B06DC; font-size: 16px; padding-top: 14px; padding-left: 6px;"/>').html('<span class="glyphicon glyphicon-certificate"></span> Generate Segment'));
    var targetMark = "#row_" + globalSelectedCampaign.replace("_MASTER_DE","");
    $(targetMark).addClass("selectedHighlight")
  };

  if (globalPaneActive == 2) {
    popActivityLog();
  };

  if (userLogin != ""){
    if (clearUndefined(userLogin[0][0]) != "") {
      if (clearUndefined(userLogin[0][1] != "")){
        setCookie('timbertoken',userLogin[0][0] + '|' + userLogin[0][1],31);
        globalPulledUser = userLogin[0][0] + '|' + userLogin[0][1];
        $('#loginStatus').addClass('loggedIn');
      };
    };
  };

  if (returnArray == "INVALID PASS") {
    eraseCookie("timbertoken");
  }

  initLogin();

  if (returnArray[0][0] == "Username Not Found"){
    $("#usernameLogin").addClass("notify");
    $('.notifications').append("Username Not Found");
  };

  if (returnArray[0][0] == "Password Email Sent"){
    $('.notifications').append("Password Email Sent");
  };

  });
 };

 /*
   We're defining the event on the `body` element,
   because we know the `body` is not going away.
   Second argument makes sure the callback only fires when
   the `click` event happens only on elements marked as `data-editable`
 */
 /*$('body').on('click', '[data-editable]', function(){

   var $el = $(this);
   var tag = $(this).prop("tagName");
   var getName = $(this).attr("name");
   var getClass = $(this).attr("class");
   var getDataDE = $(this).data("detarget");
   var getDataType = $(this).data("rowtype");
   var getDataRow = $(this).data("rowtarget");
   var lengthIn = $el.text().length + 1;

   var $input = $('<input size=' + lengthIn + ' data-original="' + $el.text() + '"/>').val( $el.text() );
   $el.replaceWith( $input );

   var save = function(){
     if ($input.val() != $el.text()) {
       var $p = $('<' + tag + ' name="' + getName + '" class="' + getClass + ' modified"' + ' data-detarget="' + getDataDE + '" data-rowtype="' + getDataType + '" data-rowtarget="' + getDataRow + '" data-editable />').text( $input.val() );
       $input.replaceWith( $p );
       collectText();
     } else {
       var $p = $('<' + tag + ' name="' + getName + '" class="' + getClass + '"' + ' data-detarget="' + getDataDE + '" data-rowtype="' + getDataType + '" data-rowtarget="' + getDataRow + '" data-editable />').text( $input.val() );
       $input.replaceWith( $p );
     }
   };


    //We're defining the callback with `one`, because we know that the element will be gone just after that, and we don't want any callbacks leftovers take memory. Next time `p` turns into `input` this single callback will be applied again.

   $input.one('blur', save).focus();

 });*/

 $('body').on('input', '[contenteditable]', function(){
   var getOriginal = $(this).data("original");
   var getHTML1 = $(this).text();
   if (getHTML1 == getOriginal) {
     $(this).removeClass('modified');
   } else {
     $(this).addClass('modified');
   }
   collectText();
 });

 $('body').on('blur', '[contenteditable]', function(){
   var getOriginal = $(this).data("original");
   var getHTML1 = $(this).text();
   if (getHTML1.trim() == "") {
     $(this).text(getOriginal);
     $(this).removeClass('modified');
   }

   collectText();
 });


var arrayToTable = function (data, indexArr, rowClass, options, appendTgt, includeDeTgt) {

  if (typeof data !== "undefined" ) {
    if (data[0][0] != ""){
      "use strict";

      var table = $('<table />'),
          thead,
          tfoot,
          rows = [],
          harray = [],
          hrow,
          hcount = 0,
          row,
          i,
          j,
          classToAdd,
          deIdentifierLength = deIdentifier.length;
          defaults = {
              th: false, // should we use th elemenst for the first row
              thead: false, //should we incldue a thead element with the first row
              tfoot: false, // should we include a tfoot element with the last row
              attrs: {} // attributes for the table element, can be used to
          };

      options = $.extend(defaults, options);

      table.attr(options.attrs);
      //table.attr('class','genTable');

      if (data == 'new'){
        var data = new Array();
        var tmpArr = new Array();
        for (a = 0; a < indexArr.length; a++){
          if (indexArr[a][3] == "true") {
            tmpArr.push([indexArr[a][0].replace("c_","")]);
          } else {
            tmpArr.push("");
          };
        };
        data.push(tmpArr);
        table.attr('class','newSegTable');
        var rowtypeNew = "new";
        var idString = "newrow_";
      };


      // loop through all the rows, we will deal with tfoot and thead later
      for (i = 0; i < data.length; i = i + 1) {
        if (data[i][0] != "") {


          //get target DE from last item in array, if it is there, indicated by detgt__, then get the substring with that removed, then save it to a variable to add into the field later ...... if new segment and campaign is selected, then use the global selected var as DE target
          var subStrCheck = data[i][data[i].length - 1].indexOf(deIdentifier);
          if (subStrCheck >= 0) {
            var dataArrLength = data[i].length - 1;
            var deTarget = data[i][data[i].length - 1].slice(deIdentifierLength);
          } else if (globalSelectedCampaign != "") {
            var dataArrLength = data[i].length;
            var deTarget = globalSelectedCampaign;
          } else {
            var dataArrLength = data[i].length;
            var deTarget = "";
          };
          var idString = "row_" + data[i][1];

          row = $('<tr />').attr('id', idString).attr('class',rowClass).attr('data-detarget', deTarget).attr('data-tgtproperty', data[i][0]);

          if (i === 0 && options.thead) {
            hrow = $('<tr />');
          };


          // length minus one - last item is the target data extension
          for (j = 0; j < dataArrLength; j = j + 1) {

              if (rowtypeNew == "new"){
                var rowtarget = "new";
                if (j == 0) {
                  rowtarget = "newRow"; //set first item to create new row
                };
                if (indexArr[j][1] == "new"){
                  var canEdit = "true";
                } else {
                  var canEdit = indexArr[j][1];
                };
              } else {
                var rowtarget = data[i][0];
                var canEdit = indexArr[j][1];
              };

              if (indexArr[j][3] == "false") {
                classToAdd = indexArr[j][0] + " hide";
              } else {
                classToAdd = indexArr[j][0] + " " + indexArr[j][4];
              };

              var dataContent = data[i][j];

              if ((dataContent == "") && (indexArr[j][3] == "true")) {
                dataContent = indexArr[j][0].replace("c_","").replace("p_","");
                classToAdd += " unfilled";
              };

              // only populate headers with data in them
              if ((dataContent != "") && (indexArr[j][3] != "false")) {
                if (harray.includes(j) == false) {
                  harray.push(j)
                  hcount = hcount + 1;
                };
              };

              //if includeDeTgt flag then include it in the ID
              var deTgtStr = "";
              if (includeDeTgt == 1) {
                deTgtStr = '_' + deTarget;
              }
              if ((j <= indexArr.length) && (indexArr != "") && (dataContent != "")) {
                  //remove identifier name and rowtype - add in ID later
                  row.append($('<td />').html(dataContent).attr('contenteditable', canEdit).attr('id', indexArr[j][0] + '_' + rowtarget + deTgtStr).attr('class', classToAdd).attr("name",indexArr[j][0].replace("c_","").replace("p_","")).attr('data-detarget', deTarget).attr('data-rowtype', indexArr[0][0].replace("c_","").replace("p_","")).attr('data-rowtarget', rowtarget).attr('data-options', indexArr[j][5]).attr('data-original', data[i][j]));
              };
          };

          row.append($('<td />').html("").attr('id', "options" + '_' + rowtarget).addClass("option" + rowClass));
          rows.push(row);
        };
      };

      // && (indexArr[j][3] != "false")

      if (options.thead) {
        for (k = 0; k < indexArr.length; k++) {
          if (k == harray[harray.length - hcount]) {
            hrow.append($('<th />').html(indexArr[k][2]));
            hcount = hcount - 1; //subtract one from hcount to count up the array
          };
        };
      };

      // if we want a thead use shift to get it
      if (options.thead) {
          thead = $('<thead />').append(hrow);
          table.append(thead);
      };

      // if we want a tfoot then pop it off for later use
      if (options.tfoot) {
          tfoot = rows.pop();
      };

      // add all the rows
      for (i = 0; i < rows.length; i = i + 1) {
          table.append(rows[i]);
      };

      // and finally add the footer if needed
      if (options.tfoot) {
          tfoot = $('<tfoot />').append(tfoot);
          table.append(tfoot);
      };

      if (typeof appendTgt !== "undefined") {
        $(appendTgt).append(row)
      };

      return table;

    };
  };
};


function setCookie(name,value,days) {
   var expires = "";
   if (days) {
       var date = new Date();
       date.setTime(date.getTime() + (days*24*60*60*1000));
       expires = "; expires=" + date.toUTCString();
   };
   document.cookie = name + "=" + (value || "")  + expires + "; path=/";
};

function getCookie(cname) {
   var name = cname + "=";
   var decodedCookie = decodeURIComponent(document.cookie);
   var ca = decodedCookie.split(';');
   for(var i = 0; i <ca.length; i++) {
       var c = ca[i];
       while (c.charAt(0) == ' ') {
           c = c.substring(1);
       }
       if (c.indexOf(name) == 0) {
           return c.substring(name.length, c.length);
       }
   }
    return "";
}

function eraseCookie(name) {
 document.cookie = name+'=; Max-Age=-99999999;';
};


</script>


</html>
