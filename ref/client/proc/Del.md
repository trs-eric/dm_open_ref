## Del proc (client)
**See also:**
+   [Logout proc (mob)](/ref/mob/proc/Logout.md) <!-- -->
**Format:**
+   Del()
<!-- -->
**When:**
+   Called when the player disconnects from the world.
<!-- -->
**Default action:**
+   If the player is connected to a mob, call mob.Logout() to
    disconnect. If the player\'s connection to the world is still not
    dead, kill it.


Note that this does not automatically delete the player\'s mob.
If you want to do that, you could do so in mob.Logout().