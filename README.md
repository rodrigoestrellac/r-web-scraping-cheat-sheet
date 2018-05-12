# Web Scraping Reference: Cheat Sheet for Web Scraping using R

inspired by Hartley Brody, this cheat sheet is about web scraping with rvest,httr and Rselenium. This is a r version of this blog https://blog.hartleybrody.com/web-scraping-cheat-sheet/. So the table of contents is similar.

While Hartley uses python's requests and beautifulsoup libraries. This cheat covers the usage of httr and rvest. In addition, usage of Rselenium(web driver) is also covered.

This cheat sheet contains many examples with real websites. Thus, if any examples do not work anymore, it may result from the changes in their HTML.

# Talbe of Contents
1. <a href="#rvest">Web Scraping using rvest and httr</a>
	1. <a href="#rvest1">Useful Libraries and Resources</a>
	1. <a href="#rvest2">Making Simple Requests</a>
	1. <a href="#rvest3">Inspecting Response</a>
	1. <a href="#rvest4">Extracting Elements from HTML</a>
	1. <a href="#rvest5">Storing Data in R</a>
		1. <a href="#rvest5.1">Storing Data as list</a>
		1. <a href="#rvest5.2">Storing Data as data.frame</a>
	1. <a href="#rvest6">Saving Data to disk</a>
		1. <a href="#rvest6.1">Saving Data to csv</a>
		1. <a href="#rvest6.2">Saving Data to SQLite Database</a>
	1. <a href="#rvest7">More Advanced Topics</a>
		1. <a href="#rvest7.1">Javascript Heavy Websites</a>
		1. <a href="#rvest7.2">Content Inside iFrames</a>
		1. <a href="#rvest7.3">Sessions and Cookies</a>
		1. <a href="#rvest7.4">Delays and Backing Off</a>
		1. <a href="#rvest7.5">Spoofing the User Agent</a>
		1. <a href="#rvest7.6">Using Proxy Servers</a>
		1. <a href="#rvest7.7">Setting Timeouts</a>
		1. <a href="#rvest7.8">Handling Network Errors</a>
1. <a href="#rselenium">Web Scraping using Rselenium</a>
	1. <a href="#rselenium1">Useful Libraries and Resources</a>

# 1. <a name="rvest">Web Scraping using rvest and httr</a>
## 1.1. <a name="rvest1">Useful Libraries and Resources</a>
## 1.2. <a name="rvest2">Making Simple Requests</a>
## 1.3. <a name="rvest3">Inspecting Response</a>
## 1.4. <a name="rvest4">Extracting Elements from HTML</a>
## 1.5. <a name="rvest5">Storing Data in R</a>
### 1.5.1. <a name="rvest5.1">Storing Data as list</a>
### 1.5.2. <a name="rvest5.2">Storing Data as data.frame</a>
## 1.6. <a name="rvest6">Saving Data to disk</a>
### 1.6.1. <a name="rvest6.1">Saving Data to csv</a>
### 1.6.2. <a name="rvest6.2">Saving Data to SQLite Database</a>
## 1.7. <a name="rvest7">More Advanced Topics</a>
### 1.7.1. <a name="rvest7.1">Javascript Heavy Websites</a>
### 1.7.2. <a name="rvest7.2">Content Inside iFrames</a>
### 1.7.3. <a name="rvest7.3">Sessions and Cookies</a>
### 1.7.4. <a name="rvest7.4">Delays and Backing Off</a>
### 1.7.5. <a name="rvest7.5">Spoofing the User Agent</a>
### 1.7.6. <a name="rvest7.6">Using Proxy Servers</a>
### 1.7.7. <a name="rvest7.7">Setting Timeouts</a>
### 1.7.8. <a name="rvest7.8">Handling Network Errors</a>
# 2. <a name="rselenium">Web Scraping using Rselenium</a>
## 2.1. <a name="rselenium1">Useful Libraries and Resources</a>
