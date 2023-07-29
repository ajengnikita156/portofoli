<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink ,Button} from 'flowbite-vue'
</script>
<template>
    <Navbar>
      <template #logo>
        <NavbarLogo link="https://www.google.com/" alt="Flowbite logo" style="margin: 10px ;" image-url="./src/logo.png" >
          PORTOFOLIO  
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">BERANDA</NavbarLink>
          <NavbarLink link="#">PROFIL</NavbarLink>
          <NavbarLink link="./src/TentangComponent.vue">PENGALAMAN</NavbarLink>
          <div class="flex items-center md:order-2">
          
           
        </div>

      </NavbarCollapse>

      </template>
    </Navbar>
</template>