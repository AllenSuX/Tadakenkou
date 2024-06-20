<template>
    <footer class="text-center mt-4 container-fluid">
      <div class=" inner row">
        <div class="maps col-sm-12  col-lg-6">
          <iframe 
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3165.9611150983956!2d138.854835710445!3d37.48524397194327!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x5ff5075246d4bfc1%3A0xe331a90d0fcfc765!2z44K_44O844OA5bu65bel!5e0!3m2!1szh-TW!2sjp!4v1718760681081!5m2!1szh-TW!2sjp" 
            width="100%" 
            height="250" 
            style="border:0;" 
            loading="lazy" 
            referrerpolicy="no-referrer-when-downgrade">
          </iframe>
        </div>
        <div class="ContactDetil col-sm-12 col-lg-6">
          <ul>
            <li>
                〒940-0016<br>
                新潟県長岡市宝３丁目４−２２<br>
                TEL：025−824−0115<br>
                FAX：025-824−0118<br>
                E-mail：kenko@ta-da.co.jp
            </li>
        </ul>
        </div>
        
    </div>
      <p>(c)ターダ建工有限会社 Co., Ltd. All Right Reserved.</p>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'Footer',
  };
  </script>
  
  <style scoped>
    footer {
      padding: 20px 20px;
      background-color: #f8f9fa;
      border-top: 1px solid #e9ecef;
      background-color: #003690;
      color: rgba(255,255,255,0.9) ;
      font-size: 1rem;
    }
    ul{
      list-style:none;
    }
    li{
      text-align: left;
    }
  </style>
  