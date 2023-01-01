```
<!DOCTYPE html>
<html lang="en">
   <head>
      <meta http-equiv="content-type" content="text/html; charset=utf-8" />
      <title>Patowmack Divers Home Page</title>
      <meta name="keywords" content="scuba diving Patowmack Divers Virginia" />
      <meta name="viewport" content="width=device-width, initial-scale=1" />
      <link rel="icon" type="image/ico" href="./favicon.ico" />
      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous" />
      <script src="https://code.jquery.com/jquery-3.6.2.min.js" integrity="sha256-2krYZKh//PcchRtd+H+VyyQoZ/e3EcrkxhM8ycwASPA=" crossorigin="anonymous"></script>
      <script>
         <!--  https://stackoverflow.com/questions/8988855/include-another-html-file-in-a-html-file -->
         $(function () {
         var includes = $('[data-include]')
         $.each(includes, function () {
         var file = $(this).data('include') + '.html'
         $(this).load(file)
         })
         })
      </script>

      <style>
         p {
             text-indent: 10px;
         }

         .dropdown-menu{
         background-color: #6699FF;
         border: 1px solid #D9534F;
         }
      </style>
   </head>

<body class="bg-info">
   <div data-include="body"></div>
   <div data-include="navsite"></div>
   <div class="container-fluid">
   <div class="row mx-4">
  
```
