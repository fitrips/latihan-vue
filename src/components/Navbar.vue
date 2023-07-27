<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar>
      <template #logo>
        <NavbarLogo link="https://www.google.com/" alt="Flowbite logo" image-url="https://i.pinimg.com/564x/b6/a6/2c/b6a62c9bae1f77e2751583ef215ec4e8.jpg">
          VILWOCHI
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Home</NavbarLink>
          <NavbarLink link="#">About</NavbarLink>
          <NavbarLink link="#">Picture</NavbarLink>
          <NavbarLink link="#">Contact</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
</template>
