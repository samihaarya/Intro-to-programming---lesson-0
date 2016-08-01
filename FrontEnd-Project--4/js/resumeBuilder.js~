var bio = {
  "name" : "Samiha",
  "role" : "FrontEnd Developer",
  "contacts" : {
    "mobile" : "9464322369",
    "email" : "samihaarya06@gmail.com</a>",
    "github" : "samihaarya",
    "twitter" : "@arya_samiha</a>",
    "location" : "Rajpura,Punjab"
  },
  "welcomeMsg" : "A Smile is the Happiness you will find right under your Nose",
  "skills" : ["HTML","CSS","JavaScript","Bootstrap","C"],
  "biopic" : "images/IMG_20160704_083344.jpg"
};
function displaybio(){
  var formattedName = HTMLheaderName.replace("%data%",bio.name);
  var formattedRole = HTMLheaderRole.replace("%data%",bio.role);
  var formattedMobile = HTMLmobile.replace("%data%",bio.contacts.mobile);
  var formattedEmail = HTMLemail.replace("%data%",bio.contacts.email);
  var formattedGithub = HTMLgithub.replace("%data%",bio.contacts.github);
  var formattedTwitter = HTMLtwitter.replace("%data%",bio.contacts.twitter);
  var formattedLocation = HTMLlocation.replace("%data%",bio.contacts.location);
  var formattedMessage = HTMLwelcomeMsg.replace("%data%",bio.welcomeMsg);
  var formattedImage = HTMLbioPic.replace("%data%",bio.biopic);
  $("#header").prepend(formattedRole);
  $("#header").prepend(formattedName);
  $("#topContacts").append(formattedMobile);
  $("#topContacts").append(formattedEmail);
  $("#topContacts").append(formattedGithub);
  $("#topContacts").append(formattedTwitter);
  $("#topContacts").append(formattedLocation);
  $("#header").append(formattedImage);
  $("#header").append(formattedMessage);
  if( bio.skills.length > 0)
  {
     $("#header").append(HTMLskillsStart);
     for(var s in bio.skills){
      var formattedSkills = HTMLskills.replace("%data%", bio.skills[s]);
      $("#skills").append(formattedSkills);
     }
   }
   $("#footerContacts").append(formattedMobile);
   $("#footerContacts").append(formattedEmail);
   $("#footerContacts").append(formattedGithub);
   $("#footerContacts").append(formattedTwitter);
   $("#footerContacts").append(formattedLocation);
};
displaybio();
//bio displayed

var work ={
  "jobs" : [
    {
      "employer" : "Chitkara University,Punjab",
      "title" : "Student",
      "dates" : "2016",
      "location" :"Jhansala, Punjab, India",
      "description" : "I am currently enrolled in 2nd year in Computer Science Engineering"
    }
  ]
};
function displaywork(){
    for(var job in work.jobs)
    {
         $("#workExperience").append(HTMLworkStart);
         var formattedEmployer = HTMLworkEmployer.replace("%data%",work.jobs[job].employer);
         var formattedTitle = HTMLworkTitle.replace("%data%", work.jobs[job].title);
         var formattedEmployerTitle = formattedEmployer + formattedTitle;

        $(".work-entry:last").append(formattedEmployerTitle);
        var formattedDates = HTMLworkDates.replace("%data%", work.jobs[job].dates);
        $(".work-entry:last").append(formattedDates);
        var formattedLocation = HTMLworkLocation.replace("%data%", work.jobs[job].location);
        $(".work-entry:last").append(formattedLocation);
        var formattedDescription = HTMLworkDescription.replace("%data%", work.jobs[job].description);
        $(".work-entry:last").append(formattedDescription);
    }
};
displaywork();
//work displayed

var education = {
  "schools" : [
    { "name" : "Patel Public School, Rajpura",
      "location" : "Rajpura, Punjab",
      "degree" : "High School",
      "dates" : "2013-2015",
      "majors" : "PCM",
      "url" : "http://patelpublicschool.com/"
    },
    { "name" : "CHITKARA UNIVERSITY",
      "location" : "Chitkara University, Jhansala, Punjab",
      "degree" : "BTech",
      "dates" : "2015-2019",
      "majors" : "CompSci",
      "url" : "http://www.chitkara.edu.in/"
    }
  ],
  "onlineCourses" : [
    {
         "title" : "Front End Nanodegree",
         "School" : "Udacity",
         "date" : "Ongoing",
	 "Url"	: "https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001"
    }
  ]
};

function displayeducation(){
  $("#education").append(HTMLschoolStart);
  if(education.schools.length > 0){
    for (var j in education.schools){
      var formattedName = HTMLschoolName.replace("%data%",education.schools[j].name);
      var formattedlocation = HTMLschoolLocation.replace("%data%",education.schools[j].location);
      var formattedDegree = HTMLschoolDegree.replace("%data%",education.schools[j].degree);
      var formattedDates = HTMLschoolDates.replace("%data%",education.schools[j].dates);
      var formattedMajor = HTMLschoolMajor.replace("%data%",education.schools[j].majors);
      var formattedUrl = HTMLschoolURL.replace("%data%",education.schools[j].majors);
      $(".education-entry:last").append(formattedName + formattedDegree);
      $(".education-entry:last").append(formattedlocation);
      $(".education-entry:last").append(formattedDates);
      $(".education-entry:last").append(formattedUrl);
    }
    $("#education").append(HTMLonlineClasses);
    $("#education").append(HTMLschoolStart);
    for( var c in education.onlineCourses){
      var formattedTitle = HTMLonlineTitle.replace("%data%",education.onlineCourses[c].title);
      var formattedSchool = HTMLonlineSchool.replace("%data%",education.onlineCourses[c].School);
      var formattedDate = HTMLonlineDates.replace("%data%",education.onlineCourses[c].date);
      var formattedUrl = HTMLonlineURL.replace("%data%",education.onlineCourses[c].Url);
      $(".education-entry:last").append(formattedTitle + formattedSchool);
      $(".education-entry:last").append(formattedDate);
      $(".education-entry:last").append(formattedUrl);
    }
  }
};
displayeducation();

var Projects = {
    "projects" :[
       {
        "title" : "SPEECH RECOGNISATION",
        "dates" : "2016-Present",
        "description" : "I worked under Chitkara University's Research Department(CURIN) on Natural Language Speech Recognisation in Punjabi Language",
        "image" : "images/image2.jpg",
        "url" : "https://www.facebook.com/Chitkara-University-Speech-Recognition-Hub-1712477912326760/"
      },
      {
        "title" : "My Portfolio",
        "dates" : "2016",
        "description" : "I have made a responsive Portfolio page using bootstrap under FrontEnd Course",
        "image" : "images/image1.png",
        "url" : "https://github.com/samihaarya/Frontend-Project--3"
     }
  ]
};
Projects.display = function(){

  if( Projects.projects.length > 0){
    for(i in Projects.projects){
      $("#projects").append(HTMLprojectStart);
      var formattedTitle = HTMLprojectTitle.replace("%data%",Projects.projects[i].title).replace("#",Projects.projects[i].url);
      $(".project-entry:last").append(formattedTitle);
      var formattedDates = HTMLprojectDates.replace("%data%",Projects.projects[i].dates);
      var formattedDescription = HTMLprojectDescription.replace("%data%",Projects.projects[i].description);
      var formattedImage = HTMLprojectImage.replace("%data%",Projects.projects[i].image);
      $(".project-entry:last").append(formattedDates);
      $(".project-entry:last").append(formattedDescription);
        $(".project-entry:last").append(formattedImage);
    }
  }
};
Projects.display();
$("#mapDiv").append(googleMap);
