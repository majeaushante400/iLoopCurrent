# iLoopCurrent
EndSwitch  $iLoopCurrent += 1 Until 0 Func _FPS()     WinSetTitle($hGui, "", "Rendering with: " &amp; $asBlittingMethod[$iBlittingMethod] &amp; " (" &amp; $iLoopCurrent &amp; " FPS)")     $iLoopCurrent = 0
