<template>
    <div class="navbar bg-base-100">
        <div class="navbar-start">
            <div class="dropdown">
                <label tabindex="0" class="btn btn-ghost lg:hidden">
                    <Icon name="ri:menu-2-fill"/>
                </label>
                <ul tabindex="0"
                    class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52">
                    <li>
                        <NuxtLink to="/">Home</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/about">About</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/projects">Projects</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/blog">Blog</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="contact">Contact</NuxtLink>
                    </li>
                </ul>
            </div>
            <a class="btn btn-ghost normal-case text-xl">daisyUI</a>
        </div>
        <div class="navbar-end hidden lg:flex">
            <ul class="menu menu-horizontal px-1">
                <li>
                    <NuxtLink to="/">Home</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/about">About</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/projects">Projects</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="/blog">Blog</NuxtLink>
                </li>
                <li>
                    <NuxtLink to="contact">Contact</NuxtLink>
                </li>
            </ul>
        </div>
    </div>
</template>