cdrtfe 1.2: Icons and glyphs
============================

Credits:
--------

- new cdrtfe 1.2 standard icons

  * Speed button glyphs and CD icon are slightly modified
    versions of icons from the Silk Icon set 1.3
    (http://www.famfamfam.com/lab/icons/silk/) by Mark James
    Creative Commons Attribution 2.5 License.

  * Opened and closed folder icons based on icons from the
    Winstripe FF classic theme (http://kmgerich.com/) by
    Stephen Horlander and Kevin Gerich. Mozilla tri-license.

  * Additional icons by Rob van Ruremonde.


Notes:
------

- The size of all icons and glyphs is 16x16 Pixel².

- The color depth is 8 or 24 Bit (256 or 16 Mio. colors).

- For all speedbutton glyphs (btn_*.bmp) the color of the
  bottom-leftmost pixel will be used as transparent color.

- For all icons (icon_*.bmp) the transparent color is
  fuchsia (RGB $FF00FF).

- The main application icon cannot be changed.

- There are 8 standard button bitmaps (btn_load_file.bmp,
  btn_load_folder.bmp, btn_del_file.bmp, btn_del_folder.bmp,
  btn_del_all.bmp, btn_check_fs.bmp, btn_a_up.bmp,
  btn_a_down.bmp). Most of them are used for multiple buttons.

- However, the bitmap of each button can be replaced. The file
  names for these additional bitmaps are shown in the list
  below (extended bitmap).

- If a bitmap is missing, the corresponding bitmap of the old
  icon set (cdrtfe 1.1) will be used instead.


List of buttons/icons with corresponding bitmaps:
-------------------------------------------------

Button                        standard bitmap    extended bitmap

Data CD

add file                      btn_load_file
add folder                    btn_load_folder
remove file                   btn_del_file
remove folder                 btn_del_folder
remove all                    btn_del_all
check filesystem              btn_check_fs


Audio CD

add track                     btn_load_file      btn_a_load_track
move track up                 btn_a_up
move track down               btn_a_down
remove track                  btn_del_file       btn_a_del_track


XCD

add file                      btn_load_file      btn_x_load_file_f1
add folder                    btn_load_folder    btn_x_load_folder
remove file                   btn_del_file       btn_x_del_file_f1
add movie/file (as form 2)    btn_load_file      btn_x_load_file_f2 
remove movie/form2 file       btn_del_file       btn_x_del_file_f2
remove folder                 btn_del_folder     btn_x_del_folder
remove all                    btn_del_all        btn_x_del_all


(S)VCD

add track                     btn_load_file      btn_v_load_track
move track up                 btn_a_up           btn_v_up
move track down               btn_a_down         btn_v_down
delete track                  btn_del_file       btn_v_del_track


Icons

CD icon                       icon_cd
folder (opened)               icon_folder_opened
folder (closed)               icon_folder_closed
DAE audiotrack icon           icon_audiotrack