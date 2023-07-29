<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink ,Button} from 'flowbite-vue'
</script>
<template>
    <Navbar>
      <template #logo>
        <NavbarLogo link="https://www.google.com/" alt="Flowbite logo" style="margin: 10px ;" image-url="https://media.istockphoto.com/id/1307140504/id/vektor/vektor-ikon-profil-pengguna-simbol-potret-avatar-logo-tanda-orang-bentuk-datar-siluet-hitam.jpg?s=170667a&w=0&k=20&c=SeSORWcv4QuPDGjYzS2TtaMjrtCyVhbve08_CFJymGg=" >
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