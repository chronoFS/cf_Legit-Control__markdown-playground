# Markdown image syntax

## Basic syntax

![Legit Playbook](https://www.legitcontrol.com/timetravel.svg)

## With optional title (tooltip)

`![alt text](url "title")`

![Legit Playbook](https://www.legitcontrol.com/timetravel.svg "Legit Time Travel")

## Relative path (image in repo)


![Local image](Image1.png)

## Reference-style image

Define the URL once, reuse by reference:

![Legit logo][logo]

[logo]: https://www.legitcontrol.com/timetravel.svg


## Images in a Table 

Some repos using Images in a Markdown table [Source](https://github.com/jwt/ruby-jwt/blob/main/README.md?plain=1)
| Logo                                                                                                             | Message                                                                                                                                                                                                                                                                  |
| ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![auth0 logo](https://user-images.githubusercontent.com/83319/31722733-de95bbde-b3ea-11e7-96bf-4f4e8f915588.png) | If you want to quickly add secure token-based authentication to Ruby projects, feel free to check Auth0's Ruby SDK and free plan at [auth0.com/developers](https://auth0.com/developers?utm_source=GHsponsor&utm_medium=GHsponsor&utm_campaign=rubyjwt&utm_content=auth) |


# Image tag <img/>

## Image Tag with external URL 
<img src="https://www.legitcontrol.com/timetravel.svg"> 

## Image Tag alignment
<img src="https://www.legitcontrol.com/timetravel.svg" alt="Playbook" align="right">

- This is just sometimes used for what make a lot of problme in all editors 

## Image Tag size
<img src="https://www.legitcontrol.com/timetravel.svg" alt="Playbook" width="200" >

## Image Tag internal URL

<img src="Image1.png"> 


