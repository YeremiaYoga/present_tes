<template>
  <div class="hello">
    <div class="">
      <div class="flex">
        <div>
          <img style="width: 100px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>23</p>
        </div>
        <div>
          <img style="width: 100px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>22</p>
        </div>
        <div>
          <img style="width: 100px; padding: 10px;" v-if="circle1 == 1" src="../assets/circ-full-putih-border.png"
            @click="circle1met" />
          <img style="width: 100px; padding: 10px;" v-if="circle1 == 2" src="../assets/circ-14-kuning.png"
            @click="circle1met" />
          <img style="width: 100px; padding: 10px;" v-if="circle1 == 3" src="../assets/circ-half-hijau.png"
            @click="circle1met" />
          <img style="width: 100px; padding: 10px;" v-if="circle1 == 4" src="../assets/circ-34-merah.png"
            @click="circle1met" />
          <img style="width: 100px; padding: 10px;" v-if="circle1 == 5" src="../assets/circ-full-biru.png"
            @click="circle1met" />
          <img style="width: 100px; padding: 10px;" v-if="circle1 == 6" src="../assets/circ-full-biru-bintang.png"
            @click="circle1met" />
          <img style="width: 100px; padding: 10px;" v-if="circle1 == 7" src="../assets/circ-full-hitam.png"
            @click="circle1met" />
          <p>21</p>
        </div>
        <div>
          <img style="width: 100px;" v-if="circle2 == 1" src="../assets/circ-full-putih-border.png" @click="circle2met" />
          <img style="width: 100px;" v-if="circle2 == 2" src="../assets/circ-14-kuning.png" @click="circle2met" />
          <img style="width: 100px;" v-if="circle2 == 3" src="../assets/circ-half-hijau.png" @click="circle2met" />
          <img style="width: 100px;" v-if="circle2 == 4" src="../assets/circ-34-merah.png" @click="circle2met" />
          <img style="width: 100px;" v-if="circle2 == 5" src="../assets/circ-full-biru.png" @click="circle2met" />
          <img style="width: 100px;" v-if="circle2 == 6" src="../assets/circ-full-biru-bintang.png" @click="circle2met" />
          <img style="width: 100px;" v-if="circle2 == 7" src="../assets/circ-full-hitam.png" @click="circle2met" />
          <p>20</p>
        </div>
      </div>
      <div class="flex">
        <div>
          <img style="width: 100px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>24</p>
        </div>
        <div>
          <img style="width: 100px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>25</p>
        </div>
        <div>
          <img style="width: 100px; padding: 10px;" v-if="circle3 == 1" src="../assets/circ-full-putih-border.png"
            @click="circle3met" />
          <img style="width: 100px; padding: 10px;" v-if="circle3 == 2" src="../assets/circ-14-kuning.png"
            @click="circle3met" />
          <img style="width: 100px; padding: 10px;" v-if="circle3 == 3" src="../assets/circ-half-hijau.png"
            @click="circle3met" />
          <img style="width: 100px; padding: 10px;" v-if="circle3 == 4" src="../assets/circ-34-merah.png"
            @click="circle3met" />
          <img style="width: 100px; padding: 10px;" v-if="circle3 == 5" src="../assets/circ-full-biru.png"
            @click="circle3met" />
          <img style="width: 100px; padding: 10px;" v-if="circle3 == 6" src="../assets/circ-full-biru-bintang.png"
            @click="circle3met" />
          <img style="width: 100px; padding: 10px;" v-if="circle3 == 7" src="../assets/circ-full-hitam.png"
            @click="circle3met" />
          <p>26</p>
        </div>
        <div>
          <img style="width: 100px;" v-if="circle4 == 1" src="../assets/circ-full-putih-border.png" @click="circle4met" />
          <img style="width: 100px;" v-if="circle4 == 2" src="../assets/circ-14-kuning.png" @click="circle4met" />
          <img style="width: 100px;" v-if="circle4 == 3" src="../assets/circ-half-hijau.png" @click="circle4met" />
          <img style="width: 100px;" v-if="circle4 == 4" src="../assets/circ-34-merah.png" @click="circle4met" />
          <img style="width: 100px;" v-if="circle4 == 5" src="../assets/circ-full-biru.png" @click="circle4met" />
          <img style="width: 100px;" v-if="circle4 == 6" src="../assets/circ-full-biru-bintang.png" @click="circle4met" />
          <img style="width: 100px;" v-if="circle4 == 7" src="../assets/circ-full-hitam.png" @click="circle4met" />
          <p>27</p>
        </div>

      </div>
      <div class="flex">
        <div>
          <img style="width: 100px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>31</p>
        </div>
        <div>
          <img style="width: 100px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>30</p>
        </div>
        <div>
          <img style="width: 100px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>29</p>
        </div>
        <div>
          <img style="width: 100px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>28</p>
        </div>

      </div>
      <div class="flex">
        <div>
          <img style="width: 100px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>32</p>
        </div>
        <div>
          <img style="width: 100px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>33</p>
        </div>
        <div>
          <img style="width: 100px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>34</p>
        </div>
        <div>
          <img style="width: 100px; padding: 10px;" src="../assets/circ-full-abu.png" />
          <p>35</p>
        </div>
        
      </div>
      
    </div>
    <div class="flex" style="margin-top: 50px;">
        <div>
          <img style="width: 100px; padding: 10px; margin-left: 50px;" src="../assets/circ-full-biru.png" />
        </div>
        <div>
          <img style="width: 100px; padding: 10px; margin-left: 50px;" src="../assets/circ-full-biru-bintang.png" />
        </div>
        <div>
          <img style="width: 100px; padding: 10px; margin-left: 50px;" src="../assets/circ-full-hitam.png" />

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
    }
  },
  methods: {
    circle1met() {
      if (this.circle1 >= 7) {
        this.circle1 = 1;
      } else {
        this.circle1++;
      }
    },
    circle2met() {
      if (this.circle2 >= 7) {
        this.circle2 = 1;
      } else {
        this.circle2++;
      }
    },
    circle3met() {
      if (this.circle3 >= 7) {
        this.circle3 = 1;
      } else {
        this.circle3++;
      }
    },
    circle4met() {
      if (this.circle4 >= 7) {
        this.circle4 = 1;
      } else {
        this.circle4++;
      }
    },
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.flex {
  display: flex;
  align-items: center;
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
