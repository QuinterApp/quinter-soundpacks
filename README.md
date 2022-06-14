# quinter-soundpacks

Soundpacks repository for the Quinter Twitter client.

## Why?

[Quinter](https://github.com/QuinterApp/Quinter) supports custom soundpacks, allowing users to customize Quinter to their liking. Before, users have had to give out Dropbox (or similar), links in order to share their packs. This repository aims to fix this problem.

## Contributing a pack.

Simply open a pull request adding your soundpack. **Make sure it goes in it's own folder!** Your pack must contain the following files.

* boundary.ogg: Sound played for when you hit the edge of the buffer.
* close.ogg: The sound for when you close a timeline.
* delete.ogg: The sound for when you delete a Tweet.
* error.ogg: The sound for when you encounter an API error.
* follow.ogg: Sound played when you follow someone.
* home.ogg: Sound played for when you get new items in your home buffer.
* like.ogg: The sound played when you like a Tweet.
* likes.ogg: Sound played when your likes timeline updates.
* list.ogg: Sound played when a list updates.
* max_length.ogg: Sound for when you type over 280 characters.
* media.ogg: Sound played when you encounter media playable in your external player.
* mentions.ogg: Sound played when you get a mention.
* messages.ogg: Sound played when you get a direct message.
* new.ogg: Sound played when a timeline has new items.
* open.ogg: Sound played when you open a timeline.
* ready.ogg: The sound played when the client is ready for use.
* search.ogg: This is the sound for when a search updates.
* send_message.ogg: Sound played when you send a message.
* send_reply.ogg: Sound played when you send a reply.
* send_retweet.ogg: Sound played when you send a retweet.
* send_tweet.ogg: The sound for when you tweet something.
* unfollow.ogg: The sound for when you unfollow someone.
* unlike.ogg: This plays when you unlike a tweet.
* user.ogg: This sound plays when a user timeline updates.
* volume_changed.ogg: Sound for when your volume changes.

## Notes

1. You can put a sound with a specific person's username in your pack as well, and that will play instead of the user.ogg sound when their timeline updates.
2. If you leave out a sound, the one from the default pack will play.
