<template>
  <div id="z">
    <div id="x"></div>
    <div id="v">RESUME</div>
    <div id="q">
      <div id="r">
        <img
          id="t"
          src="https://i.pinimg.com/236x/80/98/9b/80989b43d668b7b544e58b8d69fd719b.jpg"
        />
        <h1 style="margin-left: 20px">
          Ilham <br />
          Santoso
        </h1>
      </div>
    </div>
    <div class="ab">
      <div class="bb">
        <h2>
          PROFILE
          <hr color="black" size="1" />
        </h2>
        <div class="cb">
          <p>
            <b>NAME</b><br />
            Ilham Santoso
          </p>
          <p>
            <b>DATE OF BIRTH</b><br />
            06 Februari 2005
          </p>
          <p>
            <b>ADDRESS</b><br />
            Jl. Stasiun Jerakah <br />
            RT2 RW3 <br />
            Semarang <br />
            Indonesia
          </p>
          <p>
            <b>EMAIL</b><br />
            <u>ilhamsantoso1922@gmail.com</u>
          </p>
          <h2>
            AWARDS
            <hr color="black" size="1" />
          </h2>
          <p>
            Makan Krupuk <br />
            Balap Kelereng <br />
            Balap Karung
          </p>
          <h2>
            CONTACT
            <hr color="black" size="1" />
          </h2>
          <p><b>HOME NUMBER:</b><br />-</p>
          <p>
            <b>PHONE NUMBER<i class="fas fa-phone"></i></b><br />+62 896 7790
            3703
          </p>
          <p><b>EMAIL:</b><br />ilhamsantoso1922@gmail.com</p>
        </div>
      </div>
      <div class="db">
        <h2>
          GRAPHIC ARTIST
          <hr />
        </h2>
        <div class="eb">
          <h2 style="margin-left: 20px">
            <i class="fas fa-briefcase"></i> WORK EXPERIENCE
          </h2>
          <hr
            style="
              border: 1px dashed black;
              padding-left: 10px;
              padding-right: 10px;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>CREATIVE</b><br />Feb 2013 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>SENIOR ART DIRECTOR</b><br />Lorem ipsum dolor sit amet
                consectetur adipisicing elit.
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>CREATIVE</b><br />Feb 2013 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>SENIOR ART DIRECTOR</b><br />Lorem ipsum dolor sit amet
                consectetur adipisicing elit.
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>CREATIVE</b><br />Feb 2013 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>SENIOR ART DIRECTOR</b><br />Lorem ipsum dolor sit amet
                consectetur adipisicing elit.
              </p>
            </div>
          </div>
        </div>
        <div class="fb">
          <h2 style="margin-left: 20px">EDUCATION</h2>
          <hr
            style="
              border: 1px dashed black;
              padding-left: 10px;
              padding-right: 10px;
              margin-left: 20px;
              margin-right: 20px;
            "
          />
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>MASTER DEGREE</b><br />Feb 2011 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>UNIVERSITY OF CREATIVE MINDS</b><br />Jakarta, Indonesia.
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>MASTER DEGREE</b><br />Feb 2011 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>UNIVERSITY OF CREATIVE MINDS</b><br />Jakarta, Indonesia.
              </p>
            </div>
          </div>
          <div style="display: flex; margin-left: 20px; margin-right: 20px">
            <p><b>MASTER DEGREE</b><br />Feb 2011 - Jun 2014</p>
            <div style="margin-left: 50px">
              <p>
                <b>UNIVERSITY OF CREATIVE MINDS</b><br />Jakarta, Indonesia.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "Project2",
  computed: {
    cv2() {
      return this.$store.state.cv2;
    },
  },
};
</script>