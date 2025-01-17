Since we know about html css and js and how to use bootstrap, We will start by learning jquery basics concepts. 

We use bootstrap to make websites responsive. Open source framework to build responsive websites rapidly.
Goto getboostrap.com and download latest version.

Jquery is js library and used to manipulate html and css in easy way. it handle cross browser issues. run 
on any browser. jquery is single js file. visit jquery.com to download compressed or uncompressed files. 
to use jquery, use script tag and add in html file. 

// $ is alias for jquery. document is dom. means when document ready, when dom loaded.it means structure of pages
loaded, content like images and other things take time to load. 

$('#head').html(); $ for accessing get element by id. 
$('#para').css('color:red');
if there is any syntax error, jquery will not compete and it will let page load. 
with jquery you can build powerful ui components beta slider,beta , carousel. 

Styling with jquery. 
we can try javascript features directly in the console. 
instead of fetching element twice we can fetch in once and apply both operations at a time.
$('#head').html("this is changed text").css('color:red');

we can store element in variable and apply functions on variable. 
let changes = $('#head');
changes.html("this is changed text").css('color:red');

we can also use add and remove elements.
$('h1').addClass("m-4");
$('h1').removeClass("m-4");


we can use .children() to see the children elemnts of tag. like 
$('tbody').children();

we change color of all children
$('tbody').children().css('color: green');

we can use show and hide functions.
$('#head').hide();
$('#head').show();

we can also use toggle function like if it is shown it will be hidden and if hidden it will be shown.
$('#head').toggle();

we can use events functions easily with jquery. 

$('#head').click(function(){
    alert("hello");
    });
    // we can also use on function
    $('#head').on('click',function(){
        alert("hello");
        });