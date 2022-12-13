# FFDraft
Flatiron Phase 5 Final Project

## Project Pitch
This app is a tool for storing and keeping track of fantasy football player wishlists. 

## User Stories
- Users can create an account and login.
- Users can create a wishlist.
- Users can add player to their wishlist.
- Users can delete players from their wishlist.
- Users can rate players on need/want. 
- Users can change the rating of players. 


 ## DB Schema
 ### Wishlist
- name
- has_many :users 
- has_many :players

### Users
- name
- username
- email
- password

### Player
- name
- player_id
- position
- team
- bye_week
- want rating
- belongs_to :wishlist

![FFDraft ](https://user-images.githubusercontent.com/111094390/207455894-6447fc47-66b0-4a5e-b34f-b2e2825e70f5.jpeg)

