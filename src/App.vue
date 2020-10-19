<template>
  <div id="app">
    <div id="nav">
      <li><router-link to="/ai">AIアプリ</router-link></li>
      <li><router-link to="/chat">チャットアプリ</router-link></li>
      <li><router-link to="/analytics">分析アプリ</router-link></li>
      <li><router-link to="/webpush">Web Pushアプリ</router-link></li>
    </div>
    <router-view />
  </div>
</template>

<style src="./assets/style.css" />
