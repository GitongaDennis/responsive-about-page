/* eslint-disable */
<template>
  <div class="about-card">
    <div class="card-title">
      <img height="50px" src="https://i.pinimg.com/originals/d3/69/d9/d369d9056795f553e244da66e8297cca.png" alt="avatar" class="avatar">
      <div class="title-text-content">
    <div class="title-text-content">
      <p>About Me </p>
      <h2>Gitonga Dennis</h2>
    </div>
      </div>
  </div>
  <div class="card-content">

    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eius consequatur, libero, natus,
       autem hic saepe exercitationem expedita alias corporis quisquam reiciendis ab quaerat
        rerum itaque animi repudiandae dolor in fugit,
       ratione inventore molestiae harum accusantium dignissimos. Id praesentium
        quisquam asperiores ullam quaerat totam, voluptates esse vero repellendus amet, officiis inventore.</p>

      <table>
        <tr>
          <th>Requirement</th>
          <th>Solution</th> 
        </tr>
        <tr>
          <td>Design</td>
          <td>PhotoShop, Figma, Canva, Adobe XD</td> 
        </tr>
        <tr>
          <td>Front-end</td>
          <td>React.js, Vue.js, Nuxt.js, HTML, CSS, JavaScript</td> 
        </tr>
        <tr>
          <td>Back-end</td>
          <td>Node.js, Express.js, Mongo, GraphQL</td> 
        </tr>
        <tr>
          <td>ML</td>
          <td>ML5, TensorFlow, Algorithm Design</td> 
        </tr>
        <tr>
          <td>Shop</td>
          <td>Stripe, PayFast, E-commerce, CMS, Mpesa, PesaPal</td> 
        </tr>
      </table>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eius consequatur, libero, natus,
       autem hic saepe exercitationem expedita alias corporis quisquam reiciendis ab quaerat
        rerum itaque animi repudiandae dolor in fugit,
       ratione inventore molestiae harum accusantium dignissimos. Id praesentium
        quisquam asperiores ullam quaerat totam, voluptates esse vero repellendus amet, officiis inventore.</p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Eius consequatur, libero, natus,
       autem hic saepe exercitationem expedita alias corporis quisquam reiciendis ab quaerat
        rerum itaque animi repudiandae dolor in fugit,
       ratione inventore molestiae harum accusantium dignissimos. Id praesentium
        quisquam asperiores ullam quaerat totam, voluptates esse vero repellendus amet, officiis inventore.</p>
  </div>
      </div>
</template>

<style lang="sass" scoped>
.about-card
  min-height: calc(100vh - 150px)
  background: #333
  padding: 3em
  border-radius: 10px
  color: white
  .card-title
    display: flex
    align-items: center
    background: #222
    border-radius: 10px
    .avatar
      height: 50px
      border: 1px solid rgba(255, 255, 255, 0.4)
      border-radius: 50%
      margin: 0 30px
  .title-text-content p
    margin-bottom: 0
    color: rgb(210, 210, 210)
  .title-text-content h2
    margin-top: 0

.card-content p
  line-height: 1.5
  margin: 30px auto

table 
  border-spacing: 0px
  margin: 50px auto
  tr th, tr td
    border: 1px solid white
    border-top: none
    padding: 10px
    text-align: center
    &:first-of-type
      border-left: none
    &:nth-of-type(2)
      border-right: none

@media screen and (max-width: 530px)
  .about-card 
    padding: 1em
  .card-title h2
    font-size: 1.3em
</style>