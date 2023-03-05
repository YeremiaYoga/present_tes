<template>
  <div class="hello">
    <div class="">
      <div class="flex ">
        <div>
          <img style="width: 85px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>23</p>
        </div>
        <div>
          <img style="width: 85px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>22</p>
        </div>
        <div>

          <button :disabled="pause1" v-on:click="circle1met" v-if="circle1 == 1">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-putih-border.png" />
          </button>
          <button :disabled="pause1" v-on:click="circle1met" v-if="circle1 == 2">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-14-kuning.png" />
          </button>
          <button :disabled="pause1" v-on:click="circle1met" v-if="circle1 == 3">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-half-hijau.png" />
          </button>
          <button :disabled="pause1" v-on:click="circle1met" v-if="circle1 == 4">
            <img style="width: 85px; padding: 10px; transform: rotate(-90deg)" :disabled="pause"
              src="../assets/circ-34-merah.png" />
          </button>
          <button :disabled="pause1" v-on:click="circle1met" v-if="circle1 == 5">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-biru.png" />
          </button>
          <button :disabled="pause1" v-on:click="circle1met" v-if="circle1 == 6">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-biru-bintang.png" />
          </button>
          <button :disabled="pause1" v-on:click="circle1met" v-if="circle1 == 7">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-hitam.png" />
          </button>
          <p>21</p>
        </div>
        <div>

          <button :disabled="pause2" v-on:click="circle2met" v-if="circle2 == 1">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-putih-border.png" />
          </button>
          <button :disabled="pause2" v-on:click="circle2met" v-if="circle2 == 2">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-14-kuning.png" />
          </button>
          <button :disabled="pause2" v-on:click="circle2met" v-if="circle2 == 3">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-half-hijau.png" />
          </button>
          <button :disabled="pause2" v-on:click="circle2met" v-if="circle2 == 4">
            <img style="width: 85px; padding: 10px; transform: rotate(-90deg)" :disabled="pause"
              src="../assets/circ-34-merah.png" />
          </button>
          <button :disabled="pause2" v-on:click="circle2met" v-if="circle2 == 5">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-biru.png" />
          </button>
          <button :disabled="pause2" v-on:click="circle2met" v-if="circle2 == 6">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-biru-bintang.png" />
          </button>
          <button :disabled="pause2" v-on:click="circle2met" v-if="circle2 == 7">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-hitam.png" />
          </button>
          <p>20</p>
        </div>
      </div>
      <div class="flex">
        <div>
          <img style="width: 85px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>26</p>
        </div>
        <div>
          <img style="width: 85px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>27</p>
        </div>
        <div>

          <button :disabled="pause3" v-on:click="circle3met" v-if="circle3 == 1">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-putih-border.png" />
          </button>
          <button :disabled="pause3" v-on:click="circle3met" v-if="circle3 == 2">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-14-kuning.png" />
          </button>
          <button :disabled="pause3" v-on:click="circle3met" v-if="circle3 == 3">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-half-hijau.png" />
          </button>
          <button :disabled="pause3" v-on:click="circle3met" v-if="circle3 == 4">
            <img style="width: 85px; padding: 10px; transform: rotate(-90deg)" :disabled="pause"
              src="../assets/circ-34-merah.png" />
          </button>
          <button :disabled="pause3" v-on:click="circle3met" v-if="circle3 == 5">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-biru.png" />
          </button>
          <button :disabled="pause3" v-on:click="circle3met" v-if="circle3 == 6">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-biru-bintang.png" />
          </button>
          <button :disabled="pause3" v-on:click="circle3met" v-if="circle3 == 7">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-hitam.png" />
          </button>
          <p>28</p>
        </div>
        <div>

          <button :disabled="pause4" v-on:click="circle4met" v-if="circle4 == 1">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-putih-border.png" />
          </button>
          <button :disabled="pause4" v-on:click="circle4met" v-if="circle4 == 2">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-14-kuning.png" />
          </button>
          <button :disabled="pause4" v-on:click="circle4met" v-if="circle4 == 3">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-half-hijau.png" />
          </button>
          <button :disabled="pause4" v-on:click="circle4met" v-if="circle4 == 4">
            <img style="width: 85px; padding: 10px; transform: rotate(-90deg)" :disabled="pause"
              src="../assets/circ-34-merah.png" />
          </button>
          <button :disabled="pause4" v-on:click="circle4met" v-if="circle4 == 5">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-biru.png" />
          </button>
          <button :disabled="pause4" v-on:click="circle4met" v-if="circle4 == 6">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-biru-bintang.png" />
          </button>
          <button :disabled="pause4" v-on:click="circle4met" v-if="circle4 == 7">
            <img style="width: 85px; padding: 10px;" src="../assets/circ-full-hitam.png" />
          </button>
          <p>29</p>
        </div>

      </div>
      <div class="flex">
        <div>
          <img style="width: 85px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>35</p>
        </div>
        <div>
          <img style="width: 85px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>34</p>
        </div>
        <div>
          <img style="width: 85px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>33</p>
        </div>
        <div>
          <img style="width: 85px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>32</p>
        </div>

      </div>
      <div class="flex">
        <div>
          <img style="width: 85px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>38</p>
        </div>
        <div>
          <img style="width: 85px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>39</p>
        </div>
        <div>
          <img style="width: 85px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>40</p>
        </div>
        <div>
          <img style="width: 85px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>41</p>
        </div>

      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      circle1: 2,
      circle2: 1,
      circle3: 3,
      circle4: 4,
      pause1: false,
      pause2: false,
      pause3: false,
      pause4: false,
    }
  },
  methods: {
    circle1met() {
      if (this.circle1 >= 7) {
        this.circle1 = 1;
        this.pause1 = true;
        setTimeout(() => this.pause1 = false, 2000)
      } else {
        this.circle1++;
        this.pause1 = true;
        setTimeout(() => this.pause1 = false, 2000)
      }

    },
    circle2met() {
      if (this.circle2 >= 7) {
        this.circle2 = 1;
        this.pause2 = true;
        setTimeout(() => this.pause2 = false, 2000)
      } else {
        this.circle2++;
        this.pause2 = true;
        setTimeout(() => this.pause2 = false, 2000)
      }
    },
    circle3met() {
      if (this.circle3 >= 7) {
        this.circle3 = 1;
        this.pause3 = true;
        setTimeout(() => this.pause3 = false, 2000)
      } else {
        this.circle3++;
        this.pause3 = true;
        setTimeout(() => this.pause3 = false, 2000)
      }
    },
    circle4met() {
      if (this.circle4 >= 7) {
        this.circle4 = 1;
        this.pause4 = true;
        setTimeout(() => this.pause4 = false, 2000)
      } else {
        this.circle4++;
        this.pause4 = true;
        setTimeout(() => this.pause4 = false, 2000)
      }

    },
    cekdisable() {
      this.pause = true;
      console.log(this.pause)
      setTimeout(() => this.pause = false, 3000)
    }
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.flex {
  display: flex;
  justify-content: center;

}
button{
  padding: 0;
  border: none;
  background: none;
}

.cicle {
  width: 100px;
  height: 100px;
}

h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
