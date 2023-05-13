<!DOCTYPE html>
<html>
  <head>
    <title>Glitch Effect</title>
    <link href="https://fonts.googleapis.com/css?family=Fira+Mono:400" rel="stylesheet">
    <style>
      body{ 
        display: flex;
        width: 100vw;
        height: 100vh;
        align-items: center;
        justify-content: center;
        margin: 0;
        background: #131313;
        color: #fff;
        font-size: 96px;
        font-family: 'Fira Mono', monospace;
        letter-spacing: -7px;
      }

      div{
        animation: glitch 1s linear infinite;
      }

      div:before,
      div:after{
        content: attr(title);
        position: absolute;
        left: 0;
      }

      div:before{
        animation: glitchTop 1s linear infinite;
        clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%);
        -webkit-clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%);
      }

      div:after{
        animation: glitchBotom 1.5s linear infinite;
        clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%);
        -webkit-clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%);
      }

      @keyframes glitch{
        2%,64%{
          transform: translate(2px,0) skew(0deg);
        }
        4%,60%{
          transform: translate(-2px,0) skew(0deg);
        }
        62%{
          transform: translate(0,0) skew(5deg); 
        }
      }

      @keyframes glitchTop{
        2%,64%{
          transform: translate(2px,-2px);
        }
        4%,60%{
          transform: translate(-2px,2px);
        }
        62%{
          transform: translate(13px,-1px) skew(-13deg); 
        }
      }

      @keyframes glitchBotom{
        2%,64%{
          transform: translate(-2px,0);
        }
        4%,60%{
          transform: translate(-2px,0);
        }
        62%{
          transform: translate(-22px,5px) skew(21deg); 
        }
      }
    </style>
  </head>
  <body>
    <div title="404">404</div>
  </body>
</html>





[![Ashutosh's github activity graph](https://github-readme-activity-graph.cyclic.app/graph?username=ACHUX21&bg_color=000000&color=9e4c98&line=9e4c98&point=9c9c9c&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)
![Snake animation](https://github.com/thepiyushmalhotra/thepiyushmalhotra/blob/output/github-contribution-grid-snake.svg)
