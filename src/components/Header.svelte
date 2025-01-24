<script>
  import NavLink from "./NavLink.svelte";
  import logo from "$lib/img/LOGO.png";

    const links = [
        { name: 'The Class', href: '#the-class' },
        { name: 'The Teacher', href: '#the-teacher' },
        { name: 'Testimonials', href: '#testimonials' },
        { name: 'Questions?', href: '#questions' }
    ]
</script>

<header class="fixed w-full bg-white shadow-md z-50">
    <nav class="container mx-auto px-4 py-4 flex items-center justify-between">
        <div class="flex items-center">
            <img src={logo} alt="Fast &amp; Fun Language Logo" class="h-12">
        </div>
        <div class="mx-3 hidden md:flex space-x-6">
            {#each links as link}
                <NavLink href={link.href} title={link.name} />
            {/each}
        </div>
        <div class="flex items-center space-x-4">
            <a href="/enroll" class="btn-text bg-brand-primary text-white px-4 py-2 rounded-lg hover:opacity-90">Enroll Now</a>
            <a href="#login" class="student-icon">
                <i class="fas fa-user text-gray-400"></i>
            </a>
        </div>
    </nav>
</header>