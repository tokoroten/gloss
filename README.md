# Gloss
* original Gloss:
  * http://www.tuxradar.com/gloss/

Original Gloss is OpenGL game libraly of Python, using PyGame.
But it lacks some function to make my Game.
So, I fixed Gloss.

Original Gloss is licensed under LGPLv3. so this fixed Gloss is LGPLv3.

## fixed
* SpriteFont support multibyte string (like japanenes).
* support to switch rendering mode.
  * Gloss.draw_mode_default()
    * draw default copy.using alpha channel.
  * Gloss.draw_mode_add()
    * blend additional mode.
  * Gloss.draw_mode_sub()
    * blend subtraction mode.
  * Gloss.draw_mode_override()
    * overwrite even alpha channel.
* exit game only ESC. (original is LeftCTRL+ESC)
* support Gloss.draw_pie .
* support Gloss.draw_arc .
* Texture.Draw support scale_x, scale_y, not only scale.
* ParticleSystem support scale_x_rate.
* GL_RGBA32F_ARB is not defined my enviroment. it move to 0x8814.


# MyGame
* https://www.youtube.com/watch?v=7-hPyxorhho
* http://www.nicovideo.jp/watch/sm25185906

# contact
http://twitter.com/tokoroten
