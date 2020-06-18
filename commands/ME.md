__Set/Read the memory channel__


Set the memory channel:

	ME p1, p2, p3, p4, p5, p6, p7, p8, p9, p10, p11, p12, p13, p14, p15, p16, p17, p18

Read the memory channel:

	ME xxx
	
Returns: memory channel number (3 digit)

|p|function|
|---|---|
|1|Memory channel number 3 digit
|2|Frequency in Hz 10 digit. C clears the channel
|3|[Step size](/tables/step_size.md)
|4|[Shift direction](/tables/shift.md)
|5|[Reverse](/tables/status.md)
|6|[Tone status](/tables/status.md)
|7|[CTCSS status](/tables/status.md)
|8|[DCS status](/tables/status.md)
|9|[Cross tone]
|10|[Tone frequency](/tables/tone_ctcss.md)
|11|[CTCSS frequency](/tables/tone_ctcss.md)
|12|[DCS frequency](/tables/DCS.md)
|13|[Cross tone encode/decode]
|14|Offset frequency in Hz 8 digit
|15|[Mode](/tables/mode.md)
|16|Frequency in Hz 10 digit, or transmit freq for odd split
|17|unknown need help on this
|18|[Lock out](/tables/status.md)
