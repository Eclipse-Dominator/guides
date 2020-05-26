<header>
<navbar placement="top" type="light">
<a slot="brand" href="https://se-edu.github.io" title="More SE-EDU Resources" class="navbar-brand"><img src="https://se-edu.github.io/images/SeEduLogo.png" alt="SE-EDU" width="30"></a>
  <li><a href="{{baseUrl}}/index.html" class="nav-link"><md>Home</md></a></li>
  <li><a href="{{baseUrl}}/about.html" class="nav-link"><md>About</md></a></li>
  <li slot="right" class="nav-link">
    <form class="navbar-form">
      <searchbar :data="searchData" placeholder="Search this site" :on-hit="searchCallback" menu-align-right ></searchbar>
    </form>
  </li>
</navbar>
</header>
