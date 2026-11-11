UFU - Ultimate Football Universe (first playable)
Godot 4.2+  |  Compatibility renderer  |  Landscape

HOW TO OPEN
1. Unzip so you have a folder "UFU" containing project.godot.
2. Godot -> Import -> select UFU/project.godot -> Import & Edit.
3. Press Play (top right). Main scene = scenes/main_menu.tscn.

CONTROLS (phone): left half = floating joystick, SPRINT (hold), PASS (tap), SHOOT (hold = charge, release = kick)
CONTROLS (PC test): WASD/arrows, Shift sprint, J pass, K shoot

FILES
project.godot            settings (Compatibility renderer, landscape, autoload Game)
icon.svg
scenes/main_menu.tscn    Control + main_menu.gd
scenes/match.tscn        Node3D + match_scene.gd (builds everything in code)
scripts/game.gd          autoload: settings + button helper
scripts/main_menu.gd     Play / Training / Settings
scripts/match_scene.gd   stadium, crowd, goals, teams, camera, timer, goals, pause
scripts/athlete.gd       shared body/animation (base for player, opponent, keeper)
scripts/player.gd        your player
scripts/opponent.gd      outfield AI
scripts/goalkeeper.gd    keeper AI
scripts/ball.gd          football physics
scripts/touch_controls.gd joystick + buttons
scripts/hud.gd           scoreboard, messages, pause, full time
