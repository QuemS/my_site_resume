<template>
  <div>
    <v-header></v-header>
    <router-view class="pt-5"></router-view>
  </div>
</template>

<script>


import "@fortawesome/fontawesome-free/css/all.css";
// import "bootstrap/dist/css/bootstrap.css";

import VHeader from "./components/VHeader.vue";

export default {
  components: {
    VHeader,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Oswald&family=Roboto&display=swap');
* {
  font-family: 'Roboto', sans-serif;
  font-weight: bold;
  margin: 0;
  padding: 0;
  text-decoration: none;
  outline: none;
  border: none;
  text-transform: capitalize;
  
  
}
.margin_top{
  margin-top: 15px;
  margin-bottom: 10px;
}


a{
  text-decoration: none;
}

/*color crimsom
black #0d0d0d 
ligth-bg #1a1a1a
white #fff
light-color #aaa
box-shadow:0 0.5rem 1rem rgba(0,0,0,0.7)*/

.flex_skills{
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: center;
  gap:10px
  
}
.color_whaite{
  color: white;
}

html::-webkit-scrollbar-track {
  background: black;
}
html::-webkit-scrollbar-thumb {
  background: crimson;
}
body {
  background-color: #0e0e0e;
}
.navbar a {
  background: #1a1a1a;
  color: white;
}
.navbar i {
  color: crimson;
}
.navbar a:hover {
  background: crimson;
}
.navbar a:hover i {
  color: white;
}
.mini_navbar a {
  background-color: #1a1a1a;
  color: white;
}
.content h3 {
  color: white;
}
.content span {
  color: crimson;
}
.content p {
  color: #a7a4a4;
}
.btn {
  background: crimson;
  color: white;
}
.btn:hover {
  
  color: white;
}
.btn i {
  background: white;
  color: crimson;
}
.aboutme h1 {
  color: white;
  text-align: center;
}
.aboutme span {
  color: crimson;
}
.content_about {
  color: white;
}
.personal1 span {
  color: #dc143b;
}
.personal2 span {
  color: #dc143b;
}
.aboutme span {
  color: crimson;
}
.content_about {
  color: white;
}
.about_skills span {
  color: #dc143c;
}
.about_img {
  background: #1a1a1a;
}
.my_education span {
  color: white;
}
.my_education_content_years {
  background: #1a1a1a;
}
.get_you {
  color: white;
}
.contact_block {
  color: crimson;
}
.contact_block span {
  color: white;
}
.contact_block h3 {
  color: white;
}
.contact_input input {
  background-color: #1a1a1a;
}
.btn_message a {
  color: white;
  background-color: crimson;
}


.email_text {
  text-transform: none;
}

html {
  font-size: 62.5%;
  overflow-x: hidden;
}
html::-webkit-scrollbar {
  width: 1rem;
}
html::-webkit-scrollbar-thumb {
  border-radius: 5rem;
}
body {
  padding: 0;
}
.navbar {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  display: flex;
  z-index: 1000;
  align-items: flex-start;
  padding: 0;
}
.navbar a {
  font-size: 2.5rem;
  padding: 2rem 0 1rem 0;
  flex-grow: 1;
  text-align: center;
  transition: 0.2s linear;
}
.navbar a i {
  padding-right: 0.5rem;
}
.navbar a:hover {
  padding-top: 2rem;
}

/*mini_navbar*/

.mini_navbar {
  display: flex;
  z-index: 1000;
  justify-content: center;
}
.mini_navbar a {
  transition: 0.2s;
}
.mini_navbar a:hover {
  transform: scale(1.2);
}
.mini_navbar a {
  display: flex;
  align-items: center;
  padding: 1.5rem;
  margin: 0 1rem 1rem 1rem;
  list-style: none;
  font-size: 2.5rem;
  border-radius: 25px;
  
}

main {
  padding: 6rem 3% 1rem 3%;
}

.btn {
  display: inline-block;
  margin-top: 1rem;
  border-radius: 5rem;
  padding: 0.7rem;
  font-size: 1.7rem;
  padding-left: 2rem;
  
}

.btn i {
  height: 4rem;
  line-height: 4rem;
  width: 4rem;
  font-size: 1.7rem;
  text-align: center;
  border-radius: 50%;
  margin-left: 1rem;
  transition: 0.2s linear;
}
.btn:hover i {
  
  margin-left: 2rem;
}
.home {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  gap: 1rem;
  min-height: calc(100vh - 12rem);
}
.image {
  flex: 1 1 42rem;
  text-align: center;
}
.image img {
  height: 25rem;
  width: 25rem;
  border-radius: 47% 53% 21% 79% / 30% 40% 60% 70%;
}
.content {
  flex: 1 1 39rem;
}

.content h3 {
  font-size: 2.5rem;
  padding-bottom: 0.5rem;
  text-align: center;
}
.content span {
  font-size: 2rem;
  padding: 0.5rem 0;
  display: block;
  text-align: center;
}
.content p {
  font-size: 2rem;
  align-self: center;
}

.navbar a span {
  display: none;
}
.aboutme h1 {
  padding: 7rem 2rem 1rem 2rem;
  text-align: center;
  font-size: 4rem;
}
.table_info h2 {
  text-align: center;
  padding: 1rem 2rem 1rem 2rem;
}
.table_info {
  padding: 0 0.5rem;
  margin: auto;
}
.content {
  text-align: center;
}
.content_about h1 {
  text-align: center;
  font-size: 2rem;
}
.content_about {
  padding-top: 1rem 0 0 0.5rem;
  text-align: center;
}

.personal1 {
  padding-top: 2rem;
}
.personal1 h3 {
  padding-top: 1.5rem;
  font-size: 1.5rem;
}

.personal2 h3 {
  padding-top: 2rem;
  font-size: 1.5rem;
}
.personal3 h3 {
  font-size: 1.5rem;
  text-align: center;
  padding: 2rem 1.5rem 2rem 1.5rem;
}
.personal1 h3 + h3 + h3 {
  text-transform: none;
}
.about_flex {
  display: flex;
  flex-direction: column;
}
.about_img {
  background: #1a1a1a;
  width: 105px;
  height: 105px;
  border-radius: 1rem;
  margin: 0;
  padding-top: 1rem;
  margin-bottom: 2rem;
  transition: 0.2s;
}

.about_skills h1 {
  font-size: 4rem;
  padding: 0.5rem 0 2rem 0;
  margin-top: 4rem;
}
.about_skills img {
  margin: 0;
  border-radius: 1rem;
  width: 60px;
  height: 65px;
}
.about_skills h2 {
  font-size: 1.5rem;
  margin: 0.5rem 0 2rem 0;
}
.about_skills {
  align-items: center;
  padding: auto;
}

.about_skills {
  align-items: center;
}
.my_education_title h1 {
  display: block;
  padding: 7rem 2rem 1rem 2rem;
  text-align: center;
  font-size: 3.5rem;
}
.my_education_title span {
  color: crimson;
}
.my_education_content {
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 3.5rem;
  background: crimson;
  color: white;
  width: 8rem;
  height: 8rem;
  border-radius: 40px;
  margin: 1px 1px;
}
.my_education_content {
  margin: 0;
}
.my_education {
  display: flex;
  flex-direction: row;
  padding-left: 2rem;
}
.my_education_content_years {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 2rem 0 2rem 5rem;
  font-size: 1.5rem;
  padding: 0.1rem 2.5rem 0.1rem 2.5rem;
  border-radius: 50px;
}
.my_education_content_text {
  text-align: justify;
  border-left: 1px solid white;
  margin-left: 6rem;
  padding: 1rem 4rem 2rem 2rem;
  font-size: 1rem;
}
.my_education_content_text h1 {
  text-align: justify;
  font-size: 2rem;
}
.my_education_content_text p {
  padding: 0.4rem 0 0.4rem 0.5rem;
  text-align: left;
  font-size: 1.5rem;
}

footer {
  padding-bottom: 2rem;
}

/*CONTACT*/

.container_contact {
  padding: 1rem 1.5rem;
}
.get_you {
  padding: 1rem 3%;
  text-align: center;
}
.get_you h1 {
  text-align: center;
  padding: 1rem;
}
.get_you p {
  font-size: 1.5rem;
}
.contact_block {
  padding: 1.5rem 1rem;
  font-size: 1.2rem;
  text-align: center;
}

.contact_block h3 {
  padding: 0.7rem 1rem;
  font-size: 1.5rem;
}
.contact_input {
  text-align: center;
  padding: 1rem;
}
.contact_input input {
  text-align: center;
  font-size: 1.7rem;
  height: 4rem;
  border-radius: 25px;
  text-transform: none;
}
.contact_input_messages input {
  height: 22rem;
}
.btn_message {
  margin: 1.2rem;
  padding: 2rem;
  text-align: center;
}

.btn_message a {
  font-size: 1.7rem;
  border-radius: 5rem;
  padding: 1.5rem 4rem;
  letter-spacing: 1px;
}

/*media*/

@media (min-width: 768px) {
  html {
    font-size: 55%;
  }
  .content h3 {
    font-size: 2rem;
    text-align: start;
  }
  .content span {
    font-size: 3rem;
    text-align: start;
  }
  .image img {
    height: 30rem;
    width: 30rem;
  }
  .table_info ul {
    margin: auto;
  }
  .content {
    text-align: left;
  }
  .navbar a:hover {
    padding-top: 4rem;
  }
  .mini_navbar {
    justify-content: center;
    margin-top: 11rem;
  }
  .content_about {
    padding-top: 1rem 0 0 0.5rem;
    text-align: center;
  }
  .content_about h1 {
    display: block;
    margin: 4rem auto 1rem auto;
    text-align: center;
  }
  .personal1 {
    padding: 0 4rem 0rem 2rem;
    text-align: start;
  }
  .personal1 span {
    display: block;
    letter-spacing: 2px;
  }
  .personal2 span {
    display: block;
    letter-spacing: 2px;
  }
  .personal3 span {
    display: block;
    letter-spacing: 2px;
  }
  .personal2 {
    padding: 0 4rem 0rem 2rem;
    text-align: start;
  }
  .personal1 h3 {
    padding-top: 1.5rem;
    font-size: 1.5rem;
  }
  .personal2 h3 {
    font-size: 1.5rem;
    padding-left: 2rem;
  }
  .personal3 h3 {
    padding: 2rem 2rem 2rem auto;
  }
  .about_skills h2 {
    text-align: center;
    padding-top: 1rem;
  }
  .about_skills img {
    display: flex;
    text-align: center;
    margin: auto;
  }
  .about_flex {
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 2rem;
  }
  .about_skills h1 {
    font-size: 7rem;
  }

  .flex_skills {
    display: flex;
    flex-direction: row;
    
    gap: 3rem;
    justify-content: center;
  }
  .about_img {
    margin: 0;
  }
  .aboutme h1 {
    padding-top: 10rem;
    font-size: 6rem;
  }
  .my_education h1 {
    font-size: 6rem;
  }

  .content_about h3 {
    font-size: 2rem;
  }
  .my_education_title h1 {
    text-align: center;
    font-size: 7rem;
  }
  .about_img:hover {
    transform: scale(1.1);
    filter: drop-shadow(0px 0px 15px crimson);
  }
  .my_education_content_text h1 {
    font-size: 4rem;
    text-align: left;
  }
  .my_education_content_text p {
    font-size: 2rem;
    text-align: left;
  }
  .my_education_title {
    margin-top: 7rem;
    text-align: center;
    font-size: 4rem;
  }
  footer {
    padding-bottom: 5rem;
  }

  /*CONTACT 768px*/
  .container_contact_flex {
    display: flex;
    margin: auto;
    justify-content: space-evenly;
  }
  .contact_input_flex {
    display: flex;
  }
  .container_contact {
    margin-top: 4rem;
    padding: 1rem 2rem;
  }
  .get_you {
    text-align: justify;
  }
  .get_you h1 {
    text-align: center;
    padding: 1rem;
  }
  .get_you p {
    font-size: 2.5rem;
    padding: 2rem 2rem;
  }
  .contact_block {
    padding: 2rem 1rem;
    font-size: 1.2rem;
    text-align: left;
  }

  .contact_block h3 {
    padding: 0.7rem 1rem;
    font-size: 2rem;
  }
  .contact_input {
    text-align: center;
    padding: 1rem;
  }
  .contact_input input {
    text-align: center;
    font-size: 1.7rem;
    height: 4rem;
    border-radius: 25px;
    text-transform: none;
  }
  .contact_input_messages input {
    font-size: 3.5rem;
    height: 22rem;
  }
  .btn_message {
    margin-top: 1rem;
    text-align: right;
  }

  .btn_message a {
    font-size: 1.7rem;
    border-radius: 5rem;
    padding: 1.5rem 4rem;
    letter-spacing: 1px;
  }
}

@media (min-width: 1200px) {
  body {
    width: 80vw;
    margin: auto;
  }
  .home {
    gap: 10rem;
  }
  .image img {
    height: 38rem;
    width: 38rem;
  }
  .navbar a span {
    display: inline-block;
  }
  html {
    font-size: 70%;
  }
  .content {
    flex: 1 1 30rem;
  }
  .content a {
    margin-top: 2rem;
    margin-left: 1rem;
  }
  .content span {
    font-size: 3rem;
    padding: 0.5rem 0;
    text-align: start;
  }
  .content h3 {
    text-align: start;
  }

  .content p {
    font-size: 2rem;
  }
  main {
    padding: 9rem 9%;
  }
  .navbar a:hover {
    padding-top: 6rem;
  }
  .navbar a {
    padding: 2rem 0 2rem 0;
  }
  .content {
    text-align: left;
  }
  .flex_skills {
    display: flex;
    margin: 2rem auto 10rem auto;
    
  }
  .about_skills h1 {
    margin: 8rem auto 6rem auto;
    font-size: 7rem;
  }
  .aboutme h1 {
    margin: 7rem;
    font-size: 8rem;
  }
  .aboutme h1 {
    padding-top: 10rem;
    font-size: 6rem;
  }
  .about_img:hover {
    transform: scale(1.1);
    filter: drop-shadow(0px 0px 15px crimson);
  }
  .my_education_title h1 {
    text-align: center;
    font-size: 7rem;
  }

  .my_education h1 {
    font-size: 6rem;
  }
  footer {
    padding-bottom: 10rem;
  }

  /*CONTACT 1200PX*/

  .container_contact {
    margin-top: 4rem;
  }
  .container_contact_flex {
    display: flex;
    margin: auto;

    flex-wrap: 1 1;
  }
  .contact_input input {
    text-align: center;
    font-size: 2.5rem;
    height: 4rem;
    border-radius: 25px;
    text-transform: none;
  }
  .contact_input_messages input {
    height: 20rem;
  }
  .contact_input_messages input {
    width: 75rem;
    height: 25rem;
  }
  
}
</style>
