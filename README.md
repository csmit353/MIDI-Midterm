# MIDI-Midterm
input.onPinPressed(TouchPin.P0, function () {
    music.playTone(131, music.beat(BeatFraction.Quarter))
    basic.showLeds(`
        # # # # #
        # . . . #
        # . . . #
        # . . . #
        # # # # #
        `)
})
input.onButtonPressed(Button.AB, function () {
    music.playTone(131, music.beat(BeatFraction.Quarter))
    basic.showLeds(`
        # # # # #
        # . . . #
        # . . . #
        # . . . #
        # # # # #
        `)
})
input.onPinPressed(TouchPin.P1, function () {
    music.playTone(262, music.beat(BeatFraction.Whole))
    basic.showLeds(`
        . . # . .
        . # . # .
        # . . . #
        . # . # .
        . . # . .
        `)
})
input.onButtonPressed(Button.B, function () {
    music.playTone(262, music.beat(BeatFraction.Quarter))
    basic.showLeds(`
        . . # . .
        . # . # .
        # . . . #
        . # . # .
        . . # . .
        `)
})
input.onPinPressed(TouchPin.P2, function () {
    music.playTone(196, music.beat(BeatFraction.Whole))
    basic.showLeds(`
        . . . . .
        . # # # .
        . # . # .
        . # # # .
        . . . . .
        `)
})
input.onButtonPressed(Button.A, function () {
    music.playTone(208, music.beat(BeatFraction.Quarter))
    basic.showLeds(`
        . . . . .
        . # # # .
        . # . # .
        . # # # .
        . . . . .
        `)
})
input.onGesture(Gesture.TiltLeft, function () {
    music.playTone(196, music.beat(BeatFraction.Quarter))
    basic.showLeds(`
        . . . . .
        . . # . .
        . # . # .
        . . # . .
        . . . . .
        `)
})
basic.showString("Like A G6")
