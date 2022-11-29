# goit-markup-hw-03

Використано modern-normalize.css

================== fonts =================

Google - Raleway:700;800 , Roboto:400;500;700;900  

Secondary -  Verdana, Geneva, Tahoma, sans-serif;

================== Colors ===================

 Overlays Shadows Headings : #2E2F42 
 
 Valid fields Success messages color: #31D0AA;
 
 Body text : #434455 
 
 Helper text Deemphasized text color:#8E8F99; 
 
 Accent color Hairlines Subtle backgrounds color:#E7E9FC;
 
 Light mode backgrounds Light mode Dialogs/alerts color:#F4F4FD;
 
 =================  global =========================

*,
*::before,
*::after {
  box-sizing: border-box;
}

h1,
h2,
h3,
h4,
h5,
h6,
p,
ul {
  margin: 0;
  padding: 0;
}

body {
  background-color: var(--bg-white-color);
  color: var(--Body-text-color);
  font-family: Roboto, Verdana, Geneva, Tahoma, sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 1.5;
  letter-spacing: 0.02em;
}

img {
  display: block;
  width: 100%;
  height: auto;
}

.list {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
}

.link {
  text-decoration: none;
}

.title {
  color: var(--Headings-color);
  font-weight: 700;
}

.conteiner {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  width: 1158px;
  padding: 0 15px 0 15px;
  margin: auto;
  padding: auto;
}
