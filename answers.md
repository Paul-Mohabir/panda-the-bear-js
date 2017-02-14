1 Change profile-image
$('.profile-image').attr('src', 'http://www.iconeasy.com/icon/png/Movie%20%26%20TV/Futurama%20Vol.%206%20-%20The%20Movies/Steamboat%20Bender.png');

1 i   Change left-image
('#left-image img').attr('src', 'http://images.akamai.steamusercontent.com/ugc/531745980091038176/1126F5B3357822D385164F2C0C03B5E867306838/?interpolation=lanczos-none&output-format=jpeg&output-quality=95&fit=inside%7C268:268&composite-to%3D*%2C*%7C268%3A268&background-color=black');

2 Change title to my name
$('h1').text('Paul Mohabir')

3 change subheading
$('h3, info-title').text('My Learnin')

3 change employent infor
$('#employment h3.info-title').text('What I boss at')

4 delete time travel
$("#time-travel").parent().remove()

5 $('body').css( "background-color", "purple" );

6 $('.highlight').css('background-color', 'blue')

7 change fontfamily
$('h1').css('font-family', 'timesnewroman')

8 change radio buttons and colors
$(".action-icon-bg").css('background-color', 'red')

9 Change placeholder to idnetify yourself
$('#name').attr('placeholder', 'Identify yourself')

10 change the message to state your business
$('#message').attr('placeholder', 'State your Business')

11  $("form #name").attr("value", "I am Nemesis");

12 $("form #email").attr("value", "dr.zoidberg");

13 $('form #submit').attr('value', 'En-Gaurde')

SECTION2

Cloning Pikachu
$('#right-image img').clone().insertAfter('form')

var listItem = document.createElement('li'); var leftSpan = document.createElement('span'); var lastUpdated = document.createTextNode('Page last updated on'); var rightSpan = document.createElement('span'); var date = document.createTextNode(Date()); leftSpan.appendChild(lastUpdated); rightSpan.appendChild(date); listItem.appendChild(leftSpan); listItem.appendChild(rightSpan);
