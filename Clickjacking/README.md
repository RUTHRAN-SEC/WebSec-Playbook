# Clickjacking

## Description
Clickjacking is a web attack where an attacker tricks a user into clicking hidden or disguised elements on a malicious webpage. This is commonly done using an invisible iframe layered over a legitimate-looking page, causing the user to unknowingly perform actions such as changing settings, making payments, or granting permissions on another website.

Unlike CSRF attacks, clickjacking requires direct user interaction, such as clicking a button. CSRF protections like CSRF tokens do not prevent clickjacking because the requests are made within a valid authenticated session on the legitimate website. Therefore, additional protections such as X-Frame-Options and Content-Security-Policy (frame-ancestors) headers are required to mitigate this vulnerability.

<img width="781" height="440" alt="image" src="https://github.com/user-attachments/assets/959fdbd8-cc24-4c89-9644-15ad4162b860" />

## Risk level = High or Critical

## Constructing a Basic Clickjacking Attack

A basic clickjacking attack is created by embedding a legitimate website inside a hidden or transparent iframe over a decoy webpage. Using CSS properties such as `position`, `z-index`, and `opacity`, the attacker aligns the hidden iframe so that a victim unknowingly clicks on sensitive elements, such as buttons or links, while interacting with visible fake content. The iframe is made nearly invisible using a very low opacity value, and layering ensures the target website remains clickable beneath the decoy page. This technique tricks users into performing unintended actions on authenticated websites without their awareness.

## Platform:
#### PortSwigger Web Security Academy

## Lab reference:
