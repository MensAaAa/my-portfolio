<style>
  p {
    font-size: 22.5px;
    line-height: 30px;
    color: #222;
  }
  .welcome {
    height: 100%;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    grid-column-gap: 50px;
    align-items: center;
  }

  .welcome div {
    display: flex;
    flex-flow: column wrap;
    justify-content: center;
  }

  .logo img {
    height: 100%;
    width: 100%;
    margin: 150px 0;
    object-fit: cover;
  }
</style>

<div class="welcome">
  <div class="info">
    <h1>Welcome</h1>
    <p>
      I am Ramon, a product designer from Barcelona currently working with Red
      Bull and teaching design at SketchCasts. In the past, I’ve worked for
      clients such as Varner and Intersport.
    </p>
  </div>
  <div class="logo">
    <img src="successkid.jpg" alt="alt" />
  </div>
</div>
