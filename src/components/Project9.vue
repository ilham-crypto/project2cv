<template>
  <div id="a">
    <div id="e" v-for="row in Project9" :key="row">
      <h1 class="e" v-for="row in Project9" :key="row">
        {{ row.nama }}<br />
        <font id="f">{{ row.nama1 }}</font>
      </h1>
      <img src="ilh.jpg" />
      <br /><br />
      <div id="i">
        <h1>
          {{ row.judul5 }}
          <hr color="black" size="1" />
        </h1>
        <div class="i">
          <p>
            <b>{{ row.isi14 }}</b
            ><br />{{ row.isi15 }}
          </p>
          <p>
            <b>{{ row.isi16 }}</b
            ><br />{{ row.isi17 }}
          </p>
          <p>
            <b>{{ row.isi18 }}</b
            ><br /><u>{{ row.isi19 }}</u>
          </p>
          <p>
            <b>{{ row.isi20 }}</b
            ><br /><u>{{ row.isi21 }}</u>
          </p>
        </div>
        <h1>
          {{ row.isi22 }}
          <hr color="black" size="1" />
        </h1>
        <div class="i">
          <p>{{ row.isi23 }}</p>
          <p>{{ row.isi24 }}</p>
          <p>{{ row.isi25 }}</p>
        </div>
        <h1>
          {{ row.isi26 }}
          <hr color="black" size="1" />
        </h1>
        <div class="i">
          <ul>
            <li>{{ row.isi27 }}</li>
            <li>{{ row.isi28 }}</li>
            <li>{{ row.isi29 }}</li>
            <li>{{ row.isi30 }}</li>
          </ul>
        </div>
      </div>
    </div>
    <div id="d" v-for="row in Project9" :key="row">
      <h1>{{ row.judul }}</h1>
      <hr />
      <p>
        {{ row.isi }}
      </p>
      <h1>{{ row.judul1 }}</h1>
      <hr />
      <ul>
        <div id="c">
          <div>
            <li>{{ row.list }}</li>
            <li>{{ row.list1 }}</li>
            <li>{{ row.list2 }}</li>
          </div>
          <div id="b">
            <li>{{ row.list3 }}</li>
            <li>{{ row.list4 }}</li>
            <li>{{ row.list5 }}</li>
          </div>
        </div>
      </ul>
      <h1>{{ row.judul2 }}</h1>
      <hr />
      <p>
        <b>{{ row.isi2 }}</b
        >{{ row.isi3 }}<br />
        <b>{{ row.isi4 }}</b
        >{{ row.isi5 }}
      </p>
      <ul>
        <li>
          {{ row.list6 }}
        </li>
        <li>{{ row.list7 }}<br />{{ row.list8 }}</li>
        <li>{{ row.list9 }}<br />{{ row.list10 }}</li>
        <li>{{ row.list11 }}<br />{{ row.list12 }}</li>
        <li>{{ row.list13 }}<br />{{ row.list14 }}</li>
      </ul>
      <h1>{{ row.judul3 }}</h1>
      <hr />
      <p>
        {{ row.isi6 }}<b>{{ row.isi7 }}</b
        >{{ row.isi8 }}<br /><b>{{ row.isi9 }}</b>
      </p>
      <h1>{{ row.judul4 }}</h1>
      <hr />
      <p>
        {{ row.isi10 }}<b>{{ row.isi11 }}}</b><br />{{ row.isi12
        }}<b>{{ row.isi13 }}</b>
      </p>
    </div>
  </div>
</template>
<script>
export default {
  name: "Project9",
  computed: {
    Project9() {
      return this.$store.state.Project9;
    },
  },
};
</script>