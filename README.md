
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet">
	<style type="text/css">
		.shawon{
			position: relative;
   			left: 0;
   			bottom: 0;
   			width: 100%;
   			height: 100px;
   			background-color: #313131;
   			color: white;
   			text-align: center;
		}
    .follow img{
      width: 50px;
      height: auto;
      display: inline;
      padding: 5px;
    }
	</style>

	<title>SB Store-Demo Website</title>
</head>
<body>
	<!-- ======================Heder=========================================: -->
<header class="text-gray-700 body-font">
  <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
    <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
      <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
        <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
      </svg>
      <span class="ml-3 text-xl">SB Store</span>
    </a>
    <nav class="md:mr-auto md:ml-4 md:py-1 md:pl-4 md:border-l md:border-gray-400	flex flex-wrap items-center text-base justify-center">
      <a class="mr-5 hover:text-gray-900" href="#">Home</a>
      <a class="mr-5 hover:text-gray-900">Shop</a>
      <a class="mr-5 hover:text-gray-900">Store</a>
      <a class="mr-5 hover:text-gray-900">Seal</a>
    </nav>
    <button class="inline-flex items-center bg-gray-200 border-0 py-1 px-3 focus:outline-none hover:bg-gray-300 rounded text-base mt-4 md:mt-0">Bay  Now
      <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-1" viewBox="0 0 24 24">
        <path d="M5 12h14M12 5l7 7-7 7"></path>
      </svg>
    </button>
  </div>
</header>
<hr>
<!-- ============================1st step======================================= -->
<section class="text-gray-700 body-font">
  <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
    <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
      <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">Before they sold out
        <br class="hidden lg:inline-block">readymade gluten
      </h1>
      <p class="mb-8 leading-relaxed">You can bay most butyfull and gret mobile's and computer part on this siet. </p>
      <div class="flex justify-center">
        <button class="inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">Bay now</button>
        <button class="ml-4 inline-flex text-gray-700 bg-gray-200 border-0 py-2 px-6 focus:outline-none hover:bg-gray-300 rounded text-lg">See some prodact</button>
      </div>
    </div>
    <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
      <img class="object-cover object-center rounded" alt="hero" src="https://source.unsplash.com/720x600/?mobile, computer">
    </div>
  </div>
</section><hr> 

<!-- ===============================Futer link================================================ -->
<footer class="text-gray-700 body-font">
  <div class="container px-5 py-24 mx-auto flex md:items-center lg:items-start md:flex-row md:flex-no-wrap flex-wrap flex-col">
    <div class="w-64 flex-shrink-0 md:mx-0 mx-auto text-center md:text-left">
      <a class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
          <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
        </svg>
        <span class="ml-3 text-xl">SB Store</span>
      </a>
      <p class="mt-2 text-sm text-gray-500">You can see more prodact onthosc link </p>
    </div>
    <div class="flex-grow flex flex-wrap md:pl-20 -mb-10 md:mt-0 mt-10 md:text-left text-center">
      <div class="lg:w-1/4 md:w-1/2 w-full px-4">
        <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm mb-3">Mobile</h2>
        <nav class="list-none mb-10">
          <li>
            <a class="text-gray-600 hover:text-gray-800">Top</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">Popular</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">Usd</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">All</a>
          </li>
        </nav>
      </div>


      <div class="lg:w-1/4 md:w-1/2 w-full px-4">
        <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm mb-3">Computer</h2>
        <nav class="list-none mb-10">
          <li>
            <a class="text-gray-600 hover:text-gray-800">Top</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">Popular</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">Usd</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">All</a>
          </li>
        </nav>
      </div>


      <div class="lg:w-1/4 md:w-1/2 w-full px-4">
        <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm mb-3">More Prodct</h2>
        <nav class="list-none mb-10">
          <li>
            <a class="text-gray-600 hover:text-gray-800">Electronics</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">file/softoyer</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">hardwoyer</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800">All</a>
          </li>
        </nav>
      </div>

      <hr>
     <br>
      <br>

 
</footer>
<hr>
<!-- ===========================================================counict================================= -->
<footer class="text-gray-700 body-font">
  <div class="container px-5 py-24 mx-auto flex md:items-center lg:items-start md:flex-row md:flex-no-wrap flex-wrap flex-col">
    <div class="w-64 flex-shrink-0 md:mx-0 mx-auto text-center md:text-left">
      

      <a class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900" href="#">


        <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
          <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
        </svg>
        <span class="ml-3 text-xl">SB Store</span>
      </a>
      <p class="mt-2 text-sm text-gray-500">You can contrk with us by thous link  </p>
    </div>


    <div class="flex-grow flex flex-wrap md:pl-20 -mb-10 md:mt-0 mt-10 md:text-left text-center">
      <div class="lg:w-1/4 md:w-1/2 w-full px-4">
        <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm mb-3">Conut</h2>
        <nav class="list-none mb-10">
          <li>
            <a class="text-gray-600 hover:text-gray-800" href="#">mobile: 01720533280</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800" href="#">E-mail: shawon@gmail.com</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800" href="#">Facebook: Shawon</a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800" href="#">location</a>
          </li>
        </nav>
      </div>

       <div class="flex-grow flex flex-wrap md:pl-20 -mb-10 md:mt-0 mt-10 md:text-left text-center">
      <div class="lg:w-1/4 md:w-1/2 w-full px-4">
        <h2 class="title-font font-medium text-gray-900 tracking-widest text-sm mb-3">Follow Us</h2>
        <nav class="list-none mb-10">
          <li>
            <a class="follow" class="text-gray-600 hover:text-gray-800" href="#"><img src="facebook.png" alt="Facebook"></a>
          </li>
          <li>
            <a class="follow" class="text-gray-600 hover:text-gray-800" href="#"><img src="bird.png" alt="tuter"></a>
          </li>
          <li>
            <a class="follow" class="text-gray-600 hover:text-gray-800" href="#"><img src="photograph.png" alt="instargram"></a>
          </li>
          <li>
            <a class="text-gray-600 hover:text-gray-800" href="#">location</a>
          </li>
        </nav>
      </div>



      
      <hr>
     <br>
      <br>
      
 
</footer>
<!-- =================================futer============================================================= -->
      <dir class="shawon" style="margin: 0; padding: 0;">
      	<p style="color: #fff5; text-align: center; padding-top: 12px; width: 100%; margin: 0;">&copy copyrite by shawondeb@-2020.com</p>
      	<p style="color: #fff5; text-align: center; padding-top: 12px; width: 100%; margin: 0;">A Demo Website </p>
      </dir>

</body>
</html>
