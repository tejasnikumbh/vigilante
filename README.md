# Vigilante
![alt text](images/bot.png)
Spam Detection BOT for Telegram groups. (Tokenised Reward System)

## Summary 
Vigilante Telegram Bot rewards users that label content appropriately as spam, in groups at periodic intervals depending upon the genuineness of their tags.

## Command Interface
Vigilante Bot supports following commands:

#### Commands that work in groups

*For User*
* `/spam <in response to some content>`  - tag a piece of content as spam
* `/inappropriate <in response to some content>` - tag a piece of content as inappropriate


*For Admin*
* `/restrict @user` - restrict a user from tagging
* `/unrestrict @user` - unrestrict a user from tagging


#### Commands that work in DMs

*For User*
* `/balance` - this will show user his/her current balance


*For Admin*
* `/info accounts` - summary of all accounts of supergroup
* `/info <username>` - information about a particular user, by username
* `/award @user <amount>` - awards specified user additional tokens
* `/deduct @user <amount>` - deduct tokens from specified user

## Future Commands
- [ ] `/set_bounty <amount>` - set the rewards for tokens ahead of time
- [ ] `/redeem <amount>` - to redeem tokens in exchange of some real reward 

# Future Tasks
- [ ] Ideation and other command support.

# Author
- Tejas Nikumbh
  - tejnikumbh.compmetitions@gmail.com
  - Skype: tjnikumbh
