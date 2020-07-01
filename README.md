# mysql-base62
MySQL function for encoding UUID() hashes as a [A-Za-z0-9] character sequence

This function was taken from stackoverflow.com a long time ago, but I can't recall where. I changed it a bit to meet my needs and to make it comply to the syntax of the most recent public MySQL release.

You may actually shuffle the character sequence at your liking, provided the length of 62 characters does not change.
