@import url('https://fonts.googleapis.com/css2?family=Syne:wght@400..800&display=swap');

:root {
  --gh-font-heading: 'Syne', sans-serif;
  --gh-font-body: 'Syne', sans-serif;
  text-decoration: none;

}

body {
  font-family: var(--gh-font-body, 'Syne', sans-serif);
  background-color: #F7F9FF;
  margin: 0;
  text-decoration: none;
}

h1, h2, h3, h4, h5 {
  font-family: var(--gh-font-heading, 'Syne', sans-serif);
  text-decoration: none;

}


.label-text {
  position: relative;
  text-decoration: none;
  letter-spacing: 0.1px;
  line-height: 20px;
  font-weight: 500;
}
.state-layer {
  align-self: stretch;
  flex: 1;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 10px 12px;
  text-decoration: none;
}
.button {
  border-radius: 100px;
  height: 40px;
  overflow: hidden;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  color: #06677f !important;
}

.button:hover {
  background-color: #06677F14;
  transition: all 0.3s ease-in-out;
}
.icon {
  width: 18px;
  font-weight: 400 !important;
  font-size: 18px !important;
  position: relative;
  max-height: 100%;
  overflow: hidden;
  flex-shrink: 0;
}
.state-layer3 {
  align-self: stretch;
  flex: 1;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 10px 16px 10px 12px;
  gap: 8px;
}
.buttons {
  flex: 1;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: flex-start;
  gap: 10px;
}
.logo-child {
  width: 100%;
  position: absolute;
  margin: 0 !important;
  height: 83.78%;
  top: 16.22%;
  right: 0%;
  bottom: 0%;
  left: 0%;
  max-width: 100%;
  overflow: hidden;
  max-height: 100%;
  z-index: 0;
}
.logo {
  width: 125px;
  height: 46px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: flex-start;
  padding: 6px 0px 0px;
  box-sizing: border-box;
  position: relative;
}
.state-layer4 {
  align-self: stretch;
  color: #fff !important;
  flex: 1;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 10px 24px 10px 16px;
  gap: 8px;
}
.button4 {
  border-radius: 100px;
  background-color: #06677f;
  height: 40px;
  overflow: hidden;
  flex-shrink: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.enter {
  flex: 1;
  display: flex;
  flex-direction: row;
  align-items: flex-end;
  justify-content: end;
  color: #fff;
}
.container {
  width: 1040px;
  height: 100%;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  max-width: 1040px;
}
.sizemd {
  width: 100%;
  position: relative;
  background-color: #f7f9ff;
  height: 104px;
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  padding: 0px 40px;
  box-sizing: border-box;
  text-align: center;
  color: #F7F9FF;
}

a {
  text-decoration: none;
  color: #F7F9FF;
  font-weight: 500;
  font-size: 16px;
  line-height: 20px;
  letter-spacing: 0.1px;  
}

.footer {
  background-color: #f7f9ff;
  padding: 40px 0;
  font-family: Syne, sans-serif;
  color: #003543;
  font-size: 16px;
}
.footer-container {
  max-width: 1040px;
  margin: 0 auto;
  padding: 0 16px;
}
.footer-top {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  margin-bottom: 32px;
}
.footer-left {
  flex: 0 0 auto;
  min-width: 280px;
  width: 50%;
}
.footer-logo img {
  display: block;
}
.footer-description {
  max-width: 420px;
  margin-top: 12px;
}
.footer-right {
  display: flex;
  flex: 1;
  gap: 48px;
  flex-wrap: wrap;
  min-width: 280px;
}
.footer-links {
  list-style: none;
  padding: 0;
  flex: 1;
  font-weight: 500  !important;
}
.footer-links li:first-child {
  margin-bottom: 10px !important;
}
.footer-links li a {
  color: #003543;
  text-decoration: none;
  font-weight: 400 !important;
  display: inline-block;
  margin-bottom: 10px !important;
}
.footer-bottom {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  font-size: 13px;
}
.footer-inline-links {
  list-style: none;
  padding: 0;
  display: flex;
  gap: 16px;
}
.footer-inline-links li a {
  color: #06677f;
  text-decoration: none;
}
@media (max-width: 768px) {
  .footer-top {
    flex-direction: column;
    gap: 32px;
  }
  .footer-bottom {
    flex-direction: column;
    gap: 16px;
    text-align: center;
  }
}