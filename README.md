@import 'variables.scss';
@import 'mixins.scss';
body {
  font-family: 'Lora', 'Helvetica Neue', Helvetica, Arial, sans-serif;

  position: relative;

  width: 100%;
  height: 100%;

  color: white;
  background-color: black;
}

html {
  width: 100%;
  height: 100%;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: 'Cabin', 'Helvetica Neue', Helvetica, Arial, sans-serif;
  font-weight: 700;

  margin: 0 0 35px;

  letter-spacing: 1px;
  text-transform: uppercase;
}

p {
  font-size: 16px;
  line-height: 1.5;

  margin: 0 0 25px;
  @media(min-width: 768px) {
    font-size: 18px;
    line-height: 1.6;

    margin: 0 0 35px;
  }
}

a {
  -webkit-transition: all 0.2s ease-in-out;
  -moz-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;

  color: $primary;
  &:focus,
  &:hover {
    text-decoration: none;

    color: darken($primary, 20%);
  }
}

#mainNav {
  font-family: 'Cabin', 'Helvetica Neue', Helvetica, Arial, sans-serif;

  margin-bottom: 0;

  text-transform: uppercase;

  border-bottom: 1px solid fade-out(white, .7);
  background-color: black;
  .navbar-toggler {
    font-size: 14px;

    padding: 11px;

    color: white;
    border: 1px solid white;
  }
  .navbar-brand {
    font-weight: 700;
  }
  a {
    color: white;
  }
  .navbar-nav {
    .nav-item {
      -webkit-transition: background 0.3s ease-in-out;
      -moz-transition: background 0.3s ease-in-out;
      transition: background 0.3s ease-in-out;
      &:hover {
        color: fade(white, 80%);
        outline: none;
        background-color: transparent;
      }
      &:active,
      &:focus {
        outline: none;
        background-color: transparent;
      }
    }
  }
  @media(min-width:992px) {
    padding-top: 20px;
    padding-bottom: 20px;

    -webkit-transition: background 0.3s ease-in-out, padding-top 0.3s ease-in-out, padding-bottom 0.3s;
    -moz-transition: background 0.3s ease-in-out, padding-top 0.3s ease-in-out, padding-bottom 0.3s;
    transition: background 0.3s ease-in-out, padding-top 0.3s ease-in-out, padding-bottom 0.3s;
    letter-spacing: 1px;

    border-bottom: none;
    background: transparent;
    &.navbar-shrink {
      padding-top: 10px;
      padding-bottom: 10px;

      border-bottom: 1px solid fade-out(white, .7);
      background: black;
    }
    .nav-link.active {
      outline: none;
      background-color: rgba(white, .3);
      &:hover {
        color: white;
      }
    }
  }
}

.masthead {
  display: table;

  width: 100%;
  height: auto;
  padding: 200px 0;

  text-align: center;

  color: white;
  background: url('../img/intro-bg.jpg') no-repeat bottom center scroll;
  background-color: black;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  .intro-body {
    display: table-cell;

    vertical-align: middle;
    .brand-heading {
      font-size: 50px;
    }
    .intro-text {
      font-size: 18px;
    }
  }
  @media(min-width:768px) {
    height: 100%;
    padding: 0;
    .intro-body {
      .brand-heading {
        font-size: 100px;
      }
      .intro-text {
        font-size: 22px;
      }
    }
  }
}

.btn-circle {
  font-size: 26px;

  width: 55px;
  height: 55px;
  margin-top: 15px;
  line-height: 38px;

  -webkit-transition: background 0.3s ease-in-out;
  -moz-transition: background 0.3s ease-in-out;
  transition: background 0.3s ease-in-out;

  color: white;
  border: 2px solid white;
  border-radius: 100% !important;
  background: transparent;
  &:focus,
  &:hover {
    color: white;
    outline: none;
    background: fade-out(white, .9);
  }
}

.content-section {
  padding-top: 150px;
  padding-bottom: 150px;
}

.download-section {
  color: white;
  background: url('../img/downloads-bg.jpg') no-repeat center center scroll;
  background-color: black;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

#map {
  width: 100%;
  height: 300px;
}
@media(min-width:992px) {
  .content-section {
    padding-top: 200px;
    padding-bottom: 200px;
  }
  #map {
    height: 350px;
  }
}

.btn {
  font-family: 'Cabin', 'Helvetica Neue', Helvetica, Arial, sans-serif;
  font-weight: 400;

  -webkit-transition: all 0.3s ease-in-out;
  -moz-transition: all 0.3s ease-in-out;
  transition: all 0.3s ease-in-out;
  text-transform: uppercase;

  border-radius: 0;
}

.btn-default {
  color: $primary;
  border: 1px solid $primary;
  background-color: transparent;
  &:focus,
  &:hover {
    color: black;
    border: 1px solid $primary;
    outline: none;
    background-color: $primary;
  }
}

ul.banner-social-buttons {
  margin-top: 0;
  @media(max-width: 1199px) {
    margin-top: 15px;
  }
  @media(max-width:767px) {
    li {
      display: block;

      margin-bottom: 20px;
      padding: 0;
      &:last-child {
        margin-bottom: 0;
      }
    }
  }
}

footer {
  padding: 50px 0;
  p {
    font-size: 14px;

    margin: 0;
  }
}

::-moz-selection {
  background: #fcfcfc;
  background: fade-out(white, .8);
  text-shadow: none;
}

::selection {
  background: #fcfcfc;
  background: fade-out(white, .8);
  text-shadow: none;
}

img::selection {
  background: transparent;
}

img::-moz-selection {
  background: transparent;
}

body {
  -webkit-tap-highlight-color: fade-out(white, .8);
}

