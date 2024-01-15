<base-nav type="primary"
        v-model="showMenu3"
        >
  <a slot="brand" class="navbar-brand" href="#">Navbar</a>

  <ul class="navbar-nav">
     <li class="nav-item active">
         <a href="#pablo" class="nav-link">link</a>
     </li>
     <li class="nav-item">
         <a href="#pablo" class="nav-link">link</a>
     </li>     
  </ul>
  <form class="form-inline ml-auto" @submit.prevent="onSubmit">
      <base-input class="no-border"
                  v-model="form.input"
                  type="text"
                  placeholder="Search"/>
      <base-button type="link" icon round native-type="submit">
        <i class="tim-icons icon-zoom-split"></i>
      </base-button>
  </form>
</base-nav>