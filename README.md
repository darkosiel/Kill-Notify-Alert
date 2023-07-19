# Kill-Notify-Alert
A very basic standalone FiveM Kill Notify Alert



@params
@name(string), --player name
@xp, --what ever your adding to the player cash points you would put here
@sound(bool),  --should it play a sound? true or false
@audiofile,  --the name of the file for example (kill.ogg)
@volume, --to play sound at(float) the volume that will play the sound at)


Exports:

exports.tizzy_alert:addDeath(name, xp, sound, audiofile, volume)
exports.tizzy_alert:addKill(name, xp, sound, audiofile, volume)
