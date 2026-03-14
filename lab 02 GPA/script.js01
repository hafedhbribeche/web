functionaddCourse () {
var row = document.createElement (’div’);
row.className = ’course -row’;
row.innerHTML =
’<label >Course :</label >’ +
’<inputtype =" text" name =" course []" ’ +
’placeholder ="e.g. Mathematics" required >’ +
’<label >Credits :</label >’ +
’<inputtype =" number" name =" credits []" ’ +
’placeholder ="e.g. 3" min ="1" required >’ +
’<label >Grade:</label >’ +
’<selectname =" grade []">’ +
’<optionvalue ="4.0" >A</option >’ +
’<optionvalue ="3.0" >B</option >’ +
’<optionvalue ="2.0" >C</option >’ +
’<optionvalue ="1.0" >D</option >’ +
’<optionvalue ="0.0" >F</option >’ +
’</select >’ +
’<buttontype =" button" ’ +
’onclick =" this.parentNode.remove ()">Remove </button >’;
document.getElementById(’courses ’).appendChild(row);
}

functionvalidateForm () {
varcourses = document. querySelectorAll (’[name =" course []"] ’);
varcredits = document. querySelectorAll (’[name =" credits []"] ’);

  for (var i = 0; i < courses.length; i++) {
if (courses[i]. value === "") {
alert("All coursenamefields arerequired.");
return false;
  }
}
for (var j = 0; j < credits.length; j++) {
if (isNaN(credits[j]. value) || credits[j]. value<= 0) {
alert("Credithoursmust be positivenumbers.");
return false;
}
}
return true;
  }
