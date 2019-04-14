好例子：
8-5好例子

delete：
8-13
8-10
08-11-multi-column-text
08-17-responsive-news-grid
08-20-responsive-news-srcset-x
08-XX-responsive-news-picture
等等

响应式设计

对字体的设计：
  body {
      font-family: 'Open Sans', 'Helvetica Neue', Arial, sans-serif;
      line-height: 1.5;
    }
    @media only screen and (max-width: 37.5em) {
      h1,h2,h3,h4,h5,h6 {
        font-family: 'Open Sans Condensed', 'Arial Narrow', Arial, sans-serif;
      }
    }
高清图或多倍图或大小图查询：
 .profile-box {
      position: relative;
      height: 300px;
      background-size: cover;
      background-position: 50% 50%;
      background-image: url(img/small-cat.jpg);
    }
    @media only screen and (min-width: 600px) {
      .profile-box {
        height: 600px;
        background-image: url(img/big-cat.jpg);
      }
    }