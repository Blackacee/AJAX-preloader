# AJAX-preloader

function addPreloader() {
 // if the preloader doesn't already exist, add one to the page
 if(!document.querySelector('#preloader')) {
 var preloaderHTML = '<img id="preloader" src="https://goo.gl/cNhyvX" />';
 document.querySelector('body').innerHTML += preloaderHTML;
 }
}
function removePreloader() {
 // select the preloader element
 var preloader = document.querySelector('#preloader');
 // if it exists, remove it from the page
 if(preloader) {
 preloader.remove();
 }
}
