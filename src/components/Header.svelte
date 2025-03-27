<script>
  import logo from "$lib/img/LOGO.png";
  import HeaderItem from "./HeaderItem.svelte";``
</script>

<div class="navbar md:px-8 py-3 shadow-lg bg-white">
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
        <li><a href="#how-it-works">The Class</a></li>
        <li><a href="/the-teacher">The Teacher</a></li>
        <li><a href="/questions">Questions</a></li>
      </ul>
    </div>
    <a href="/" class="cursor-pointer">
      <img src={logo} alt="logo" class="h-12 md:h-18" />
    </a>
  </div>
  <div class="navbar-center hidden lg:flex">
    <ul class="menu menu-xl font-accent text-[#000000] menu-horizontal">
      <HeaderItem title={'The Class'} link={'/#how-it-works'}/>
      <HeaderItem title={'The Teacher'} link={'/the-teacher'} />
      <HeaderItem title={'Testimonials'} link={'/testimonials'} />
    </ul>
  </div>
  <div class="navbar-end">
    <a class="btn bg-yellow-500 text-white mr-2 text-2xl p-6 font-accent rounded-full min-w-[240px] hidden">Student Login</a>
    <a href="/book" class="btn bg-[#EE6352] text-white text-2xl md:p-6 font-accent rounded-full md:min-w-[240px] shadow-xl hover:scale-102 transition-transform duration-50 ease-in-out">Book Now</a>
  </div>
</div>
