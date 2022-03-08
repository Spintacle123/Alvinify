<template>
  <el-container style="height: 93vh;font-family: Helvetica Neue">
  <el-container style="height: 93vh;font-family: Helvetica Neue">
    <el-aside width="250px" class="a-padding" style="background: rgb(255,255,255);background: linear-gradient(175deg, rgba(255,255,255,1) 0%, rgba(238,238,238,1) 100%, rgba(255,255,255,1) 100%); overflow:hidden">
      <el-row gutter="10">
         <img :src="'https://i.ibb.co/wKnJWhc/logo.png'" style="border-radius: 7px" width="210" alt=""> 


        <!-- <el-button type="danger" style="margin: 20px" round>
          <i class="el-icon-caret-bottom"></i>
          Danger
        </el-button> -->
      </el-row>
      <el-row class="m-title-b mt-4">
        <span>Browse Music</span>
      </el-row>
      <el-row  gutter="2">
        <el-menu class="row-t" :default-openeds="['1', '3']">
          <el-menu-item index="1">
            <i class="el-icon-files"></i>
            <span class="m-title">Discover</span>
          </el-menu-item>
          <el-menu-item index="2">
            <i class="el-icon-notebook-2"></i>
            <span class="m-title">Genres</span>
          </el-menu-item>
          <el-menu-item index="3">
            <i class="el-icon-data-analysis"></i>
            <span class="m-title">Top Charts</span>
          </el-menu-item>
          <el-menu-item index="4">
            <i class="el-icon-finished"></i>
            <span class="m-title">Radio</span>
          </el-menu-item>
        </el-menu>
      </el-row>
      <el-row class="m-title-b mt-3">
        <span>Your Music</span>
      </el-row>
      <el-row gutter="2">
        <el-menu class="row-t" :default-openeds="['1', '3']">
          <el-menu-item index="1">
            <i class="el-icon-collection-tag"></i>
            <span class="m-title">Favourites</span>
          </el-menu-item>
          <el-menu-item index="2">
            <i class="el-icon-refresh-right"></i>
            <span class="m-title">History</span>
          </el-menu-item>
        </el-menu>
      </el-row>
      <el-row class="m-title-b mt-3">
        <span>Your Playlist</span>
      </el-row>
      <el-row gutter="2">
        <el-menu class="row-t" :default-openeds="['1', '3']">
          <el-menu-item index="1">
            <svg style="margin-right:10px" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" width="1.3em" height="1.3em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 512 512"><path fill="currentColor" d="M256 152h208v32H256z"/><path fill="currentColor" d="M176 256h288v32H176z"/><path fill="currentColor" d="M176 360h288v32H176z"/><path fill="currentColor" d="M192 152h-64V88H96v64H32v32h64v64h32v-64h64v-32z"/></svg>
            <span class="m-title">New Playlist</span>
          </el-menu-item>
          <el-menu-item index="2">
            <svg style="margin-right:10px"  xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" width="1.3em" height="1.3em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 32 32"><path d="M4 6h18v2H4z" fill="currentColor"/><path d="M4 12h18v2H4z" fill="currentColor"/><path d="M4 18h12v2H4z" fill="currentColor"/><path d="M21 18l7 5l-7 5V18z" fill="currentColor"/></svg>
            <span class="m-title">Playlist 1</span>
          </el-menu-item>
        </el-menu>
      </el-row>
    
    </el-aside>
    
      <el-container style="overflow-x:hidden">
        <el-main style="padding:0px;overflow-x:hidden" >
          <el-row style="padding:0px" class="bg-img-1">
            <el-col :span="24" style="height: 55vh">
              <div class="grid-content">
                <el-row type="flex" justify="space-between" align="middle" style="padding: 10px 30px">
                    <el-col :span="1" class="d-flex-middle">
                      <el-button size="small" icon="el-icon-back" class="transparent" circle></el-button>
                      <el-button size="small" icon="el-icon-right" class="transparent" circle></el-button>
                    </el-col>
                    <el-col :span="1" class="d-flex-middle">
                    <el-badge is-dot class="item">
                      <svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" width="1.5em" height="1.5em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 16 16"><g fill="#ffffff"><path d="M8 16a2 2 0 0 0 2-2H6a2 2 0 0 0 2 2zm.995-14.901a1 1 0 1 0-1.99 0A5.002 5.002 0 0 0 3 6c0 1.098-.5 6-2 7h14c-1.5-1-2-5.902-2-7c0-2.42-1.72-4.44-4.005-4.901z"/></g></svg>
                    </el-badge>
                    <div style="margin-left:20px">
                      <el-avatar size="small" src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcSVUyDmcnDRPC5wIcZ4pBChLjmOzg9E6fF9qKfgp2MYk_tY7set"></el-avatar>
                    </div>
                  </el-col>
                </el-row>  
                <el-row  align="left" style="padding: 50px 70px">
                  <el-col :span="24">
                    <el-button type="info">Feature</el-button>
                  </el-col>
                  <el-col :span="24">
                    <h1 class="main-title">What's hot this weekend</h1>
                  </el-col>
                  <el-col :span="24" >
                    <p class="exp">But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born and I will give you a complete account of the system</p>
                  </el-col>
                  <el-col :span="24" class="mt-3">
                    <el-button type="danger play-btn">
                      PLAY
                    </el-button>
                    <el-button type="play-btn transparent" circle>
                      <i class="el-icon-collection-tag"></i>
                    </el-button>
                    <el-button type="play-btn transparent" circle>
                      <i class="el-icon-share"></i>
                    </el-button>
                  </el-col>
                </el-row>  
              </div>
            </el-col>
            <el-col :span="24" style="height:25vh">
              <div class="grid-content">
                <el-row  style="padding: 10px 30px">
                  <el-col :span="24" >
                    <p class="m-title-b" style="padding-left:0px">Recommended Album</p>
                  </el-col>
                </el-row>
                <el-row style="padding: 10px 30px" gutter="25">
                  <el-col style="overflow-x:hidden" :span="3" v-for="(o, index) in 8" :key="o">
                    <el-card :body-style="{ padding: '0px', textAlign: 'center', border: '0px;', boxShadow: 'none'}">
                      <img height="150" fit="none"  style="border-radius: 10px;box-shadow: -1px 17px 31px -17px rgba(0,0,0,0.14);-webkit-box-shadow: -1px 17px 31px -17px rgba(0,0,0,0.14);-moz-box-shadow: -1px 17px 31px -17px rgba(0,0,0,0.14);" :src="generateImage()" class="image">
                      <div style="padding: 14px;">
                        <span class="m-title">{{songs[index].title}}</span>
                        <div>
                          <time class="time">{{songs[index].singer}}</time>
                        </div>
                      </div>
                    </el-card>
                  </el-col>
                </el-row>
              </div>
            </el-col>
          
            <el-col :span="12" style="height:35vh;margin-top: 50px">
                <div class="grid-content" style="height: 200px">
                <el-row  style="padding: 10px 30px;">
                  <el-col :span="24" >
                    <p class="m-title-b" style="padding-left:0px;padding-bottom: 20px">Top 100 Philippines</p>
                  </el-col>
                  <el-col :span="24" v-for="a in songs.slice(0,4)" :key="a.id" style="padding: 5px 10px">
                    <el-row :gutter="50" type="flex" align="middle">
                      <el-col :span="1">
                          <span class="title">{{a.id}}</span> 
                      </el-col>
                      <el-col :span="2">
                          <img :src="generateImage()" style="border-radius: 7px" width="50" alt=""> 
                      </el-col>
                      <el-col :span="16">
                          <p class="title-b">{{a.title}}</p>
                          <span class="title">{{a.singer}}</span>
                      </el-col>
                      <el-col :span="2">
                          <p class="title">01:00</p>
                      </el-col>
                      <el-col :span="2">
                          <svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 32 32"><circle cx="8" cy="16" r="2" fill="currentColor"/><circle cx="16" cy="16" r="2" fill="currentColor"/><circle cx="24" cy="16" r="2" fill="currentColor"/></svg>
                      </el-col>
                    </el-row> 
                  </el-col>
                </el-row>
              </div>
            </el-col>
            <el-col :span="12" style="height:35vh;margin-top: 50px">
                <div class="grid-content" style="height: 200px">
                <el-row  style="padding: 10px 30px;">
                  <el-col :span="24" >
                    <p class="m-title-b" style="padding-left:0px;padding-bottom: 20px">Top 100 Philippines</p>
                  </el-col>
                  <el-col :span="24" v-for="a in songs.slice(0,4)" :key="a.id" style="padding: 5px 10px">
                    <el-row :gutter="50" type="flex" align="middle">
                      <el-col :span="1">
                          <span class="title">{{a.id}}</span> 
                      </el-col>
                      <el-col :span="2">
                          <img :src="generateImage()" style="border-radius: 7px" width="50" alt=""> 
                      </el-col>
                      <el-col :span="16">
                          <p class="title-b">{{a.title}}</p>
                          <span class="title">{{a.singer}}</span>
                      </el-col>
                      <el-col :span="2">
                          <p class="title">01:00</p>
                      </el-col>
                      <el-col :span="2">
                          <svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 32 32"><circle cx="8" cy="16" r="2" fill="currentColor"/><circle cx="16" cy="16" r="2" fill="currentColor"/><circle cx="24" cy="16" r="2" fill="currentColor"/></svg>
                      </el-col>
                    </el-row> 
                  </el-col>
                </el-row>
              </div>
            </el-col>
            <el-col :span="24" style="height:12vh">
              <div class="grid-content">
                <el-row  style="padding: 10px 30px">
                  <el-col :span="24" >
                    <p class="m-title-b" style="padding-left:0px">Genres & Moods</p>
                  </el-col>
                </el-row>
                <el-row style="padding: 10px 40px" gutter="25">
                  <el-button type="danger" size="medium" v-for="x in genres.slice(0,1)" :key="x.id">{{x}}</el-button>
                  <el-button  type="info" size="mdedium" class="btn" v-for="x in genres.slice(2)" :key="x.id">{{x}}</el-button>
                </el-row>
              </div>
            </el-col>
             <el-col :span="24" style="height:25vh">
              <div class="grid-content">
                <el-row style="padding: 10px 40px" gutter="25">
                  <el-col :span="6">
                      <img class="bg-1" style="border-radius: 7px" width="350" height="230px" alt=""> 

                      <!-- <el-card class="box-card" :style="generateBgImage()">
                        <div slot="header" class="clearfix">
                          <el-button type="danger" size="mini" >Feature</el-button>
                          <el-button style="float: right; padding: 3px 0" type="text">Operation button</el-button>
                        </div>
                        <div v-for="o in 4" :key="o" class="text item">
                          {{'List item ' + o }}
                        </div>
                      </el-card> -->
                  </el-col>
                  <el-col :span="6">
                        <img class="bg-2" style="border-radius: 7px" width="350" height="230px" alt=""> 
                  </el-col>
                  <el-col :span="6">
                        <img class="bg-3" style="border-radius: 7px" width="350" height="230px" alt=""> 
                  </el-col>
                  <el-col :span="6">
                        <img class="bg-1" style="border-radius: 7px" width="350" height="230px" alt=""> 
                  </el-col>
                
                </el-row>
              </div>
            </el-col>
          </el-row>
        </el-main>
      </el-container>
  </el-container>
  <el-footer style="height:7vh;box-shadow: -3px -13px 38px -4px rgba(0,0,0,0.16);webkit-box-shadow: -3px -13px 38px -4px rgba(0,0,0,0.16);-moz-box-shadow: -3px -13px 38px -4px rgba(0,0,0,0.16);">
    <el-row type="flex" justfy="space-between" align="middle" style="padding: 5px 6px 6px 6px">
       <el-col :span="1">
          <img :src="generateImage()" style="border-radius: 7px" width="50" alt=""> 
      </el-col>
      <el-col :span="5">
          <p class="title-b">{{songs[2].title}}</p>
          <p class="title" style="line-heigth: 9px">{{songs[2].singer}}</p>
      </el-col>
      <el-col :span="12" style="display:flex; justify-content:center;align-items:center">
        <el-row :span="24" type="flex" justify="space-between" align="middle">
          <!-- <vue-audio file="/musc/Dr\ dre.mp3"></vue-audio> -->
          <el-col align="middle" style="display:flex; align-items:center">
              <svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 15 15"><g transform="rotate(180 7.5 7.5)"><g fill="none"><path fill-rule="evenodd" clip-rule="evenodd" d="M13.05 2.75a.55.55 0 1 0-1.1 0v4.533a.5.5 0 0 0-.217-.225l-9-4.75A.5.5 0 0 0 2 2.75v9.5a.5.5 0 0 0 .733.442l9-4.75a.5.5 0 0 0 .217-.225v4.533a.55.55 0 0 0 1.1 0v-9.5zM3 11.42V3.58l7.429 3.92L3 11.42z" fill="#888888"/></g></g></svg>
              <svg style="cursor:pointer" @click="setToState(true)" v-if="!isPlaying" xmlns="http://www.w3.org/2000/svg" class="ml-2 mr-2" aria-hidden="true" role="img" width="2.5em" height="2.5em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 1024 1024"><path fill="currentColor" d="M512 64a448 448 0 1 1 0 896a448 448 0 0 1 0-896zm0 832a384 384 0 0 0 0-768a384 384 0 0 0 0 768zm-48-247.616L668.608 512L464 375.616v272.768zm10.624-342.656l249.472 166.336a48 48 0 0 1 0 79.872L474.624 718.272A48 48 0 0 1 400 678.336V345.6a48 48 0 0 1 74.624-39.936z"/></svg>
              <svg style="cursor:pointer"  @click="setToState(false)" v-else  class="ml-2 mr-2" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" width="2.5em" height="2.5em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><g fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><path d="M10 15V9"/><path d="M14 15V9"/></g></svg>
              <svg xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 15 15"><g fill="none"><path fill-rule="evenodd" clip-rule="evenodd" d="M13.05 2.75a.55.55 0 1 0-1.1 0v4.533a.5.5 0 0 0-.217-.225l-9-4.75A.5.5 0 0 0 2 2.75v9.5a.5.5 0 0 0 .733.442l9-4.75a.5.5 0 0 0 .217-.225v4.533a.55.55 0 0 0 1.1 0v-9.5zM3 11.42V3.58l7.429 3.92L3 11.42z" fill="#888888"/></g></svg>
          </el-col>     
        </el-row>
         <!-- <el-row :span="24">
             <el-col align="middle" style="display:flex; align-items:center">
              <el-slider v-model="value1"></el-slider>   
          </el-col>
         </el-row> -->
      </el-col>
       <el-col :span="6" style="display:flex; justify-content:end;align-items:center" >
          <svg class="ml-2" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" width="1.2em" height="1.2em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 256 256"><path d="M237.7 178.3a8.1 8.1 0 0 1 0 11.4l-24 24a8.2 8.2 0 0 1-11.4 0a8.1 8.1 0 0 1 0-11.4l10.4-10.3h-11.8a72.2 72.2 0 0 1-58.6-30.2l-41.7-58.3A56.1 56.1 0 0 0 55.1 80H32a8 8 0 0 1 0-16h23.1a72.2 72.2 0 0 1 58.6 30.2l41.7 58.3a56.1 56.1 0 0 0 45.5 23.5h11.8l-10.4-10.3a8.1 8.1 0 0 1 11.4-11.4zM143 107a8 8 0 0 0 11.2-1.9l1.2-1.6A56.1 56.1 0 0 1 200.9 80h11.8l-10.4 10.3a8.1 8.1 0 0 0 0 11.4a8.2 8.2 0 0 0 11.4 0l24-24a8.1 8.1 0 0 0 0-11.4l-24-24a8.1 8.1 0 0 0-11.4 11.4L212.7 64h-11.8a72.2 72.2 0 0 0-58.6 30.2l-1.1 1.6A8 8 0 0 0 143 107zm-30 42a8 8 0 0 0-11.2 1.9l-1.2 1.6A56.1 56.1 0 0 1 55.1 176H32a8 8 0 0 0 0 16h23.1a72.2 72.2 0 0 0 58.6-30.2l1.1-1.6A8 8 0 0 0 113 149z" fill="#888888"/></svg>
          <svg class="ml-2" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><g fill="none" stroke="#888888" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M17 1l4 4l-4 4"/><path d="M3 11V9a4 4 0 0 1 4-4h14"/><path d="M7 23l-4-4l4-4"/><path d="M21 13v2a4 4 0 0 1-4 4H3"/></g></svg>
          <svg class="ml-2" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" width="1em" height="1em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 512 512"><path d="M320 320c9.74-19.38 16-40.84 16-64c0-23.48-6-44.42-16-64" fill="none" stroke="#888888" stroke-linecap="square" stroke-miterlimit="10" stroke-width="32"/><path d="M368 368c19.48-33.92 32-64.06 32-112s-12-77.74-32-112" fill="none" stroke="#888888" stroke-linecap="square" stroke-miterlimit="10" stroke-width="32"/><path d="M416 416c30-46 48-91.43 48-160s-18-113-48-160" fill="none" stroke="#888888" stroke-linecap="square" stroke-miterlimit="10" stroke-width="32"/><path d="M125.65 176.1H32v159.8h93.65L256 440V72L125.65 176.1z" fill="#888888"/></svg>
          <svg class="ml-2" xmlns="http://www.w3.org/2000/svg" aria-hidden="true" role="img" width="1.2em" height="1.2em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><path d="M14 10H3v2h11v-2zm0-4H3v2h11V6zm4 8v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zM3 16h7v-2H3v2z" fill="#888888"/></svg>
      </el-col>
    </el-row>
  </el-footer>

  </el-container>
</template>

<script>


export default {
  name: 'IndexPage',
   data() {
    return {
      isPlaying: false,
      value1: 0,
      input: '',
      songs: [
        {
          id: "01",
          title: "I Am the Best",
          singer: "	2NE1"
        },
        {
          id: "02",
          title: "Margaritaville",
          singer: "	Jimmy Buffett"
        },
        {
          id: "03",
          title: "Lean On Me",
          singer: "Sandro Cavazza"
        },
        {
          id: "04",
          title: "Walking in Memphis",
          singer: "Marc Cohn"
        },
        {
          id: "05",
          title: "Meet in the Middle",
          singer: "Diamond Rio"
        },
        {
          id: "06",
          title: "Fire and Flames",
          singer: "DragonForce"
        },
        {
          id: "07",
          title: "Ah! Leah!",
          singer: "Donnie Iris"
        },
        {
          id: "08",
          title: "Through the Fire",
          singer: "DragonForce"
        },
      ],
      genres:["Blues", "Classic","Country","Dance","Electronics","Hip-hop","Jazz","Latin","Metal","Party","R&B","Reggae/Dancehall","Soundtracks","World"],
      currentDate: new Date()
    }
  },
  methods:{
    setToState(state){
      this.isPlaying = state
    },
    formatTooltip(val) {
        return val / 100;
      },
    generateImage(){
      return "https://picsum.photos/seed/"+Math.floor(Math.random() * 20) + 1+"/200"
    },
    generateWord(){
      return "https://random-words-api.vercel.app/"
    },
    generateBgImage(){
      return "background-image:url('https://picsum.photos/seed/"+Math.floor(Math.random() * 20) + 1+"/200'); background-position: top;background-size: cover;background-repeat: no-repeat;"
    },
  }
}
</script>

<style>
  .main-title{
    font-size: 70px;
    color: #fff;
    width: 40%;
    line-height: 75px;
    margin-top: 20px;
  }
  .exp{
    width: 40%;
    margin-top: 20px;
    color: #ffffffb8
  }
  el-row {
    margin-bottom: 40px;
    &:last-child {
      margin-bottom: 0;
    }
  }
  .el-col {
    border-radius: 4px;
  }
  .bg-purple-dark {
    background: #99a9bf;
  }
  .bg-purple {
    background: #d3dce6;
  }
  .bg-purple-light {
    background: #e5e9f2;
  }
  .grid-content {
    border-radius: 0px;
  }
  .row-bg {
    padding: 10px 0;
    background-color: #f9fafc;
  }
  .time {
    font-size: 13px;
    color: #999;
  }
  
  .bottom {
    margin-top: 13px;
    line-height: 12px;
  }

  .button {
    padding: 0;
    float: right;
  }

  .image {
    width: 100%;
    display: block;
  }

  .clearfix:before,
  .clearfix:after {
      display: table;
      content: "";
  }
  
  .clearfix:after {
      clear: both
  }
</style>

