<template>
  <div id="app">
    <div id="nav">
      <li><router-link to="/ai">AIアプリへ</router-link></li>
      <li><router-link to="/chat">チャットアプリへ</router-link></li>
      <li><router-link to="/analytics">分析アプリへ</router-link></li>
      <li><router-link to="/webpush">Web Pushアプリへ</router-link></li>
    </div>
    <router-view />
  </div>
</template>

<style src="./assets/style.css" />
