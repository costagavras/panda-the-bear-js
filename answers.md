1.1 Select the element that contains the profile image (hint: look for the class). Change the src attribute so it points to a picture of your choosing instead.
var profImage = document.querySelector('.profile-image');
profImage.src = "https://placebear.com/400/400";

1.2 Use the same approach to select the element that contains the photo of the sky and change the src attribute to another picture URL of your choosing.
var skyImage = document.querySelector('.portfolio-image img');
skyImage.src = "https://placebear.com/325/225";

2 Select the heading that says "Panda the Bear" and change it to your own name.
var headName = document.querySelector('h1', 'highlight');
headName.innerText = 'Constantine';

3 Select the heading that says "Employment" and change it to something else.
var employment = document.querySelector('#employment .info-title');
employment.innerText = "Something else"

4 Change the colour of the body.
var BodyColour = document.querySelector('body');
var BodyColour.style.backgroundColor='red';

5 Change the colour of each element using the highlight class. Use a for loop to do this.
var highLights = document.querySelectorAll('.highlight');
for (var i = 0; i < highLights.length; i++) {
       highLights[i].style.backgroundColor = "blue";}

6 Change the font family of the h1 to 'monospace'.
var fontH1 = document.querySelector('h1');
fontH1.style.fontFamily = "monospace";

7 Find a way to select the round icons in the sidebar and then change their colour.
var icons = document.querySelectorAll('.action-icon-bg');
for (var i = 0; i < icons.length; i++) {
       icons[i].style.backgroundColor = "white";}

8 Scroll down to the contact form. Change the placeholder attribute of the name field to "identify yourself".
var formName = document.querySelector('form #name');
formName.placeholder = "Identify yourself";

9 Change the placeholder attribute of the message field to "state your business".
var formMessage = document.querySelector('form #message');
formMessage.placeholder = "State your business";

10 Give the name field a "value" attribute of "your nemesis".
var formName = document.querySelector('form #name');
formName.value = "koala";

11 Change the value attribute of the email field to "koalathebear@gmail.com".
var formEmail = document.querySelector('form #email');
formEmail.value = 'koalathebear@gmail.com';

12 Change the value of the submit button on the contact form to "En garde!".
var formSubmit = document.querySelector('form #submit');
formSubmit.value = "En garde!";

13 We should stop Koala from sending an email to Panda that they might regret! Find a way to disable the submit button (hint: familiarize yourself with the disabled attribute).
var formSubmit = document.querySelector('form #submit');
formSubmit.disabled = true;

14 We should help Panda protect their privacy by erasing their personal details from the sidebar.
var infoPrivate = document.querySelectorAll('.bio-info-value');
for (var i = 0; i < infoPrivate.length; i++) {
       infoPrivate[i].innerText = "";}
