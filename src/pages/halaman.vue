<template>
    <Layout>
        <head>
            <link rel="stylesheet" href="style.css" />
            <title> Navibar Learning</title>
        </head>
        <body>
            <div class="fContainer">
               <nav class="wrapper">
                <div class="brand">
                    <div class="firstname">Bilkis</div>
                    <div class="lastname">Nisa</div>
                </div>
                <ul class="navigation">
                    <li><a href="/">health</a></li>
                    <li><a href="/" class="active_">home</a></li>
                    <li><a href="/">religion</a></li>
                </ul>
            </nav>
            </div>
                
        
        </body>
      
    </Layout>
  </template>
  
  <script>
  export default {
    metaInfo: {
      title: 'About us'
    }
  }
  </script>