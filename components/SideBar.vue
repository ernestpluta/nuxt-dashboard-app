<template>
<div class="sidebar w-72 fixed">
    <div class="sidebar-wrapper mt-20 h-full">
        <div class="logo flex mb-24 ml-12">
            <img src="/logo.svg" alt="logo">
            <p class="text-2xl font-semibold">Dashhy.</p>
        </div>
        <div class="main-menu ml-12">
            <p class="paragraph text-xs text-secondary uppercase mb-5 tracking-wide">Main Menu</p>
            <ul class="nav">
                <li class="nav-item flex py-5"><img src="~/assets/dashboard.svg" class="mr-5" alt="dashboard"><NuxtLink to="/" class="font-bold text-base">Dashboard</NuxtLink></li>
                <li class="nav-item flex py-5"><img src="~/assets/orders.svg" class="mr-5" alt="orders"><NuxtLink to="/" class="font-semibold text-base  text-secondary">Orders</NuxtLink></li>
                <li class="nav-item flex py-5"><img src="~/assets/customers.svg" class="mr-5" alt="customers"><NuxtLink to="/" class="font-semibold text-base text-secondary">Customers</NuxtLink></li>
                <li class="nav-item flex py-5"><img src="~/assets/messages.svg" class="mr-5" alt="messages"><NuxtLink to="/" class="font-semibold text-base text-secondary">Messages</NuxtLink></li>
            </ul>
        </div>
        <hr class="separator my-16"/>
        <div class="preferences ml-12">
            <p class="paragraph text-xs text-secondary uppercase mb-5 tracking-wide">Preferences</p>
            <ul class="nav">
                <li class="nav-item flex py-5"><img src="~/assets/settings.svg" class="mr-5" alt="settings"><NuxtLink to="/" class="font-semibold text-base text-secondary">Settings</NuxtLink></li>
                <li class="nav-item flex py-5"><img src="~/assets/support.svg" class="mr-5" alt="support"><NuxtLink to="/" class="font-semibold text-base  text-secondary">Support</NuxtLink></li>
            </ul>
        </div>
        <div class="account-details ml-12 flex flex-col mt-96">
            <div class="profile flex items-center cursor-pointer">
                <div>
                    <img src="~/assets/jane-doe.png" class="w-[40px]" alt="profile picture">
                </div>
                <div class="ml-4">
                    <p class="font-bold text-xl">Jane Doe</p>
                    <p class="text-xs text-secondary">SuperAdmin</p>
                </div>
            </div>
        </div>
    </div>
</div>
</template>
<script setup>


</script>