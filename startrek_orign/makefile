CC	= cc
#CFLAGS=     -O -DSCORE -DCAPTURE -DCLOAKING -Wno-unused-result
CFLAGS	= -O -g
# CFLAGS=     -O -Wno-unused-result
OBJS	= startrek.o
LIBS	= -lm
PROGS	= startrek

.c.o:
	$(CC) $(CFLAGS) -c $<

OFILES=     sst.o finish.o reports.o setup.o osx.o moving.o battle.o events.o ai.o planets.o

HFILES=     sst.h

sst:  $(OFILES)
	#gcc  -o sst $(OFILES) -lm
	$(CC)  -o	sst $(OFILES)	-lm
clean:
	rm $(OFILES)
        
$(OFILES):  $(HFILES)

