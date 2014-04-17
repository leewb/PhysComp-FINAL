PhysComp-FINAL
==============

/*
 * Classroom of The Future: Prospective Orb (Arduino + Processing)
 * Lee Saynor
 * DIGF 2B03 Physical Computing
 * OCAD University
 * Created April 3, 2014; Updated April 16, 2014
 * 
 *   V0 - Deprecated Java fixed, XML parser rewritten with assistance from Daniel Tabak
 *        ttslib ditched for because it interrupts draw (threading doesn't fix); GoogleTTS works
 *        timed text replaces scrolling and is synced to TTS .mp3 file duration
 *   V1 - Now fetches suggestions when about to reach ArrayList size instead arbitrary 10s (BUT
 *        this is causing IndexOutOfBounds when Google doesn't have anything), added bg sound,
 *        serial communication for LDR sensor & LED phases, only proceeds when ball is held
 *
 * 
 * Seer types query, as long as ball is held program will reveal Suggestions.
 *
 * Based on:
 * "Codebox: Amuse yourself with Google Autocomplete," MAKE by Andrew Odewahn
 * http://makezine.com/2010/11/01/codebox-amuse-yourself-with-google/
 * "Text-to-speech" by Amnon P5
 * http://amnonp5.wordpress.com/2011/11/26/text-to-speech/
 * Connecting Arduino to Processing ...to Arduino, Sparkfun
 * https://learn.sparkfun.com/tutorials/connecting-arduino-to-processing/to-arduino
 * Crossfade RGB LEDs, Learning Arduino by Clay Shirky
 * http://www.arduino.cc/en/Tutorial/DimmingLEDs
 *
 *
 */
