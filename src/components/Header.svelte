<script>
  import logo from "$lib/img/LOGO.png";
</script>

<div class="navbar bg-base-100 shadow-sm md:px-8 py-3">
  <div class="navbar-start">
    <div class="dropdown">
      <div tabindex="0" role="button" class="btn btn-ghost lg:hidden">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-5 w-5"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h8m-8 6h16"
          />
        </svg>
      </div>
      <ul
        tabindex="0"
        class="menu menu-sm dropdown-content font-heading bg-base-100 rounded-box z-1 mt-3 w-52 p-2 shadow"
      >
        <li><a href="/the-class">The Class</a></li>
        <li><a href="the-teacher">The Teacher</a></li>
        <li><a href="questions">Questions</a></li>
      </ul>
    </div>
    <a href="/" class="cursor-pointer">
      <img src={logo} alt="logo" class="h-12 md:h-18" />
    </a>
  </div>
  <div class="navbar-center hidden lg:flex">
    <ul class="menu menu-xl font-accent text-[#16455c] menu-horizontal px-1">
      <li><a href="the-class" class="text-3xl mt-1">The Class</a></li>
      <li><a href="the-teacher" class="text-3xl mt-1">The Teacher</a></li>
      <li><a href="questions" class="text-3xl mt-1">Questions</a></li>
    </ul>
  </div>
  <div class="navbar-end">
    <a class="btn bg-accent text-white text-3xl p-8 font-accent">Enroll Now</a>
  </div>
</div>
