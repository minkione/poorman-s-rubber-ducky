# Poor man's Rubber Ducky Script Converter

#Change log:
v1.1:
 > Keys added:
   * KEY_TAB
   * KEY_DEL
   * KEY_ALT
   * KEY_CTRL
   * KEY_SHIFT
   * KEY_WIN
   [Works with both PRESS and COMBINE commands]
 > New commands added:
   * COMBINE CTRL ALT DEL #presses CTRL+ALT+DEL at the same time
   * [COMBINE can use all keys + numbers + TAB,DEL,ALT,CTRL,SHIFT,WIN]
 
v1.0:
 > Script Created
 > Available commands:
   * PRINT string   #types string then hits enter
   * DELAY 1000     #sleeps for 1 second
   * WIN r          #presses windows key and r key at the same time
   * ALT x          #presses alt key and x key at the same time
   * CTRL c         #presses ctrl key and c key at the same time
   * SHIFT a        #can you guess? yes... shift + a
   * PRESS ENTER    #presses enter
   * INDICATOR=TRUE # enables indicator. which makes DigiSpark's LED flash when the script is done
