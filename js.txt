// alert("hi kaka");
var button = document.querySelector(".btn");
var firstBanner = document.querySelector(".middleBanar");
var bodyWhole = document.body
var hidding = document.querySelector(".hide");
var closeBar = document.querySelector(".fas");



button.addEventListener("click", function(){
// alert("Iam clicked");
bodyWhole.classList.add("color-overlay");
// hidding.classList.add("hide");
if(hidding.classList.contains("hide")){
  hidding.classList.remove("hide");
} else{
  hidding.classList.add("hide");
}
})


closeBar.addEventListener("click", function(){
  // alert("hi")
  bodyWhole.classList.remove("color-overlay");
  hidding.classList.add("hide");
})
