# tasmota-rules
Set of my favorite rules for tasmota.

1)
Rule1 ON Power1#State=1 DO RuleTimer1 210 ENDON ON Power1#Boot DO RuleTimer1 210 ENDON ON Rules#Timer=1 DO Power1 off ENDON
