BBOalert,Precision
# Precision based on the books Precision Today and Precision 101
    Javascript,https://github.com/stanmaz/BBOalert/blob/master/Plugins/stanmazPlugin.js
    Shortcut,prehi,Hi! Precision: 1C 16+; 1D may be short; 1NT 14-16 balanced; UDA\n

    Trusted

## Openings

    Option,Precision,enigmisto+bhohe,enigmisto+billhohe
    ,1C,Artificial 16+ pts
    ,1D,11-15 pts; 2+!D; denies 5-card major
    ,1H,11-15 pts; 5+!H
    ,1S,11-15 pts; 5+!S
    ,1N,14-16 pts; balanced
    ,2C,Artificial: 11-15 pts; 6+!C
    ,2D,Artificial: 11-15 pts; three-suited with short diamonds
    ,2H,weak preempt; 5-6!H
    ,2S,weak preempt; 5-6!S
    ,2N,22-23 pts; balanced

    Untrusted

    ,3C,weak preempt; 7!C
    ,3D,weak preempt; 7!D
    ,3H,weak preempt; 7!H
    ,3S,weak preempt; 7!S
    ,3N,solid 7+ card minor suit
    ,4C,8+ !H with strong hand
    ,4D,8+ !S with strong hand

## Development

    1N--,2C,Stayman; 9+ pts; might not have 4-card major
    1N--,2D,Transfer to hearts; 5+!H
    1N--2D--,2H,Accept transfer
    1N--2D--,3H,Super-accept transfer; 4+!H and max NT hand
    1N--2H--,2S,Accept transfer
    1N--2H--,3S,Super-accept transfer; 4+!S and max NT hand
    1N--,2H,Transfer to spades; 5+!S
    1N--,2S,Transfer to clubs; 6+!C
    1N--2S--,2N,Not interested in 3NT
    1N--2S--2N--,3C,correct to !C
    1N--2S--2N--,3D,game forcing strength; short !D
    1N--2S--2N--,3H,game forcing strength; short !H
    1N--2S--2N--,3S,game forcing strength; short !S
    1N--2S--,3C,Accept transfer with interest in 3NT
    1N--2S--3C--,3D,game forcing strength; short !D
    1N--2S--3C--,3H,game forcing strength; short !H
    1N--2S--3C--,3S,game forcing strength; short !S    
    1N--,2N,Transfer to diamonds; 6+!D
    1N--2N--,3C,Not interested in 3NT
    1N--2N--3C--,3D,correct to !D
    1N--2N--3C--,3H,game forcing strength; short !H
    1N--2N--3C--,3S,game forcing strength; short !S
    1N--2N--,3D,Accept transfer with interest in 3NT
    1N--2N--3D--,3H,game forcing strength; short !H
    1N--2N--3D--,3S,game forcing strength; short !S

    1C--,1D,0-7 pts
    1C--1D--,1N,17-19 pts; balanced
    1C--1D--,2N,20-21 pts; balanced
    1C--1D--,3N,24-26 pts; balanced
    1C--1D--1N--,2C,Stayman; 6+ pts; might not have 4-card major
    1C--1D--1N--,2D,Transfer to hearts; 5+!H
    1C--1D--1N--,2H,Transfer to spades; 5+!S
    1C--1D--1N--,2S,Transfer to clubs; 6+!C
    1C--1D--1N--2S--,2N,Not interested in 3NT
    1C--1D--1N--2S--2N--,3C,correct to !C
    1C--1D--1N--2S--2N--,3D,game forcing strength; short !D
    1C--1D--1N--2S--2N--,3H,game forcing strength; short !H
    1C--1D--1N--2S--2N--,3S,game forcing strength; short !S
    1C--1D--1N--2S--,3C,Accept transfer with interest in 3NT
    1C--1D--1N--2S--3C--,3D,game forcing strength; short !D
    1C--1D--1N--2S--3C--,3H,game forcing strength; short !H
    1C--1D--1N--2S--3C--,3S,game forcing strength; short !S    
    1C--1D--1N--,2N,Transfer to diamonds; 6+!D
    1C--1D--1N--2N--,3C,Not interested in 3NT
    1C--1D--1N--2N--3C--,3D,correct to !D
    1C--1D--1N--2N--3C--,3H,game forcing strength; short !H
    1C--1D--1N--2N--3C--,3S,game forcing strength; short !S
    1C--1D--1N--2N--,3D,Accept transfer with interest in 3NT
    1C--1D--1N--2N--3D--,3H,game forcing strength; short !H
    1C--1D--1N--2N--3D--,3S,game forcing strength; short !S

    1C--1D--,1H,5+!H
    1C--1D--,1S,5+!S
    1C--1D--,2C,5+!C
    1C--1D--,2D,5+!D
    1C--1D--,2H,5+!H; 21+ pts
    1C--1D--,2S,5+!S; 21+ pts
    1C--1D--,3C,5+!C; 21+ pts
    1C--1D--,3D,5+!D; 21+ pts
    1C--1D--,3H,strong hand with long solid !H
    1C--1D--,3S,strong hand with long solid !S
    
    1C--,2H,4-7 pts; 6+!H
    1C--,2S,4-7 pts; 6+!S
    1C--2[HS]--,2N,Asks partner to show singleton or void
    1C--2[HS]--2N--,3C,0-1!C
    1C--2[HS]--2N--,3D,0-1!D
    1C--2H--2N--,3H,Denies singleton or void
    1C--2S--2N--,3H,0-1!H
    1C--2H--2N--,3S,0-1!S
    1C--2S--2N--,3S,Denies singleton or void
    1C--,1H,8+ pts; transfer to spades; 5+!S
    1C--1H--,1S,accept transfer
    1C--1H--1S--,1N,0-2 control points (A=2;K=1)
    1C--1H--1S--,2C,3 control points (A=2;K=1)
    1C--1H--1S--,2D,4 control points (A=2;K=1)
    1C--1H--1S--,2H,5 control points (A=2;K=1)
    1C--,1S,8+ pts; transfer to clubs; 5+!C
    1C--1S--,2C,accept transfer
    1C--1S--2C--,2D,0-2 control points (A=2;K=1)
    1C--1S--2C--,2H,3 control points (A=2;K=1)
    1C--1S--2C--,2S,4 control points (A=2;K=1)
    1C--1S--2C--,2N,5 control points (A=2;K=1)
    1C--,2C,8+ pts; transfer to diamonds; 5+!D
    1C--2C--,2D,accept transfer
    1C--2C--2D--,2H,0-2 control points (A=2;K=1)
    1C--2C--2D--,2S,3 control points (A=2;K=1)
    1C--2C--2D--,2N,4 control points (A=2;K=1)
    1C--2C--2D--,3C,5 control points (A=2;K=1)
    1C--,2D,8+ pts; transfer to hearts; 5+!H
    1C--2D--,2H,accept transfer
    1C--2D--2H--,2S,0-2 control points (A=2;K=1)
    1C--2D--2H--,2N,3 control points (A=2;K=1)
    1C--2D--2H--,3C,4 control points (A=2;K=1)
    1C--2D--2H--,3D,5 control points (A=2;K=1)

    1C--,1N,8-13 pts; balanced; no 5-card suit
    1C--,2N,14+ pts; balanced; no 5-card suit; forcing to 4NT
    1C--1N--,2C,Stayman
    1C--1N--,2D,5+!D
    1C--1N--,2H,5+!H
    1C--1N--,2S,5+!S
    1C--1N--,3C,5+!C
    1C--1N--,3D,5+!D; slam interest
    1C--1N--,3H,5+!H; slam interest
    1C--1N--,3S,5+!S; slam interest
    1C--1N--,4C,5+!C; slam interest
    1C--2N--,3C,Stayman
    1C--2N--,3D,5+!D
    1C--2N--,3H,5+!H
    1C--2N--,3S,5+!S
    
    1C--,3C,4-4-4-1 shape with black singleton; usually less than 12 HCP
    1C--3C--,3D,artificial;ask partner to clarify singleton
    1C--3C--3D--,3H,!C singleton
    1C--3C--3D--,3S,!S singleton
    1C--,3D,4-4-4-1 shape with red singleton; usually less than 12 HCP
    1C--3D--,3H,artificial;ask partner to clarify singleton
    1C--3D--3H--,3S,!D singleton
    1C--3D--3H--,3N,!H singleton
    1C--,3H,4-4-4-1 shape with !S singleton; usually 12+ HCP
    1C--3H--,3S,accepts transfer; asks for control points
    1C--3H--3S--,3N,4 control points (A=2;K=1)
    1C--3H--3S--,4C,5 control points (A=2;K=1)
    1C--3H--3S--,4D,6 control points (A=2;K=1)
    1C--,3N,4-4-4-1 shape with !C singleton; usually 12+ HCP
    1C--3N--,4C,accepts transfer; asks for control points
    1C--3N--4C--,4D,4 control points (A=2;K=1)
    1C--3N--4C--,4H,5 control points (A=2;K=1)
    1C--3N--4C--,4S,6 control points (A=2;K=1)
    1C--,4C,4-4-4-1 shape with !D singleton; usually 12+ HCP
    1C--4C--,4D,accepts transfer; asks for control points
    1C--4C--4D--,4H,4 control points (A=2;K=1)
    1C--4C--4D--,4S,5 control points (A=2;K=1)
    1C--4C--4D--,4N,6 control points (A=2;K=1)
    1C--,4D,4-4-4-1 shape with !H singleton; usually 12+ HCP
    1C--4D--,4H,accepts transfer; asks for control points
    1C--4D--4H--,4S,4 control points (A=2;K=1)
    1C--4D--4H--,4N,5 control points (A=2;K=1)
    1C--4D--4H--,5C,6 control points (A=2;K=1)
    1C--,3S,transfer to 3NT with solid 7-8 card suit
    1C--3S--,4C,asks for control points
    1C--3S--4C--,4D,0-2 control points (A=2;K=1)
    1C--3S--4C--,4H,3 control points (A=2;K=1)
    1C--3S--4C--,4S,4 control points (A=2;K=1)
    1C--3S--4C--,4N,5 control points (A=2;K=1)
    1C--3S--,4D,Which is your suit?
    1C--3S--4D--,4H,solid !H
    1C--3S--4D--,4S,solid !S
    1C--3S--4D--,4N,solid !D
    1C--3S--4D--,5C,solid !C
    1C--3S--,4H,5+!H
    1C--3S--,4S,5+!S
    
    1C--,4N,Asks for Aces
    1C--4N--,5C,0 Aces
    1C--4N--,5D,1 Ace
    1C--4N--,5H,2 Aces
    1C--4N--,5S,3 Aces
    1C--4N--,5N,4 Aces

    1CDb,--,0-4 pts
    1CDb,1D,5-7 pts
    1CDb,Rd,8+ pts
    1C1[DHS],Db,5-8 pts
    1C1[DHS],1N,9-13 pts; balanced; stopper
    1C1[DHS],2N,14+ pts; balanced; stopper
    1C1D,2D,9+ pts; balanced; no stopper
    1C1D,1H,9+ pts; 5+!H
    1C1D,1S,9+ pts; 5+!S
    1C1D,2C,9+ pts; 5+!C
    1C1H,2H,9+ pts; balanced; no stopper
    1C1H,1S,9+ pts; 5+!S
    1C1H,2C,9+ pts; 5+!C
    1C1H,2D,9+ pts; 5+!D    
    1C1S,2S,9+ pts; balanced; no stopper
    1C1S,2C,9+ pts; 5+!C
    1C1S,2D,9+ pts; 5+!D
    1C1S,2H,9+ pts; 5+!H
    1C2[CDHS],Db,6-8 pts
    1C2[CDHS],2N,8-10 or 14+ pts; balanced; stopper
    1C2[CDHS],3N,11-13 pts; balanced; stopper
    1C2C,3C,9+ pts; balanced; no stopper
    1C2C,2D,9+ pts; 5+!D
    1C2C,2H,9+ pts; 5+!H
    1C2C,2S,9+ pts; 5+!S
    1C2D,3D,9+ pts; balanced; no stopper
    1C2D,2H,9+ pts; 5+!H
    1C2D,2S,9+ pts; 5+!S
    1C2D,3C,9+ pts; 5+!C
    1C2H,3H,9+ pts; balanced; no stopper
    1C2H,2S,9+ pts; 5+!S
    1C2H,3C,9+ pts; 5+!C
    1C2H,3D,9+ pts; 5+!D
    1C2S,3S,9+ pts; balanced; no stopper
    1C2S,3C,9+ pts; 5+!C
    1C2S,3D,9+ pts; 5+!D
    1C2S,3H,9+ pts; 5+!H

    1C3[CDHS],Db,balanced; interested in competing
    1C3[CDHS],3N,8-11 pts; balanced; stopper
    1C3C,3D,game forcing;5+!D
    1C3[CD],3H,game forcing;5+!H
    1C3[CDH],3S,game forcing;5+!Sed
    1CDb1D--,2N,20-21 pts; balanced
    1CDb1D--,3N,24-26 pts; balanced
    1CDb1D--1N--,2C,Stayman; 6+ pts; might not have 4-card major
    1CDb1D--1N--,2D,Transfer to hearts; 5+!H
    1CDb1D--1N--,2H,Transfer to spades; 5+!S
    1CDb1D--1N--,2S,Transfer to clubs; 6+!C
    1CDb1D--1N--2S--,2N,Not interested in 3NT
    1CDb1D--1N--2S--2N--,3C,correct to !C
    1CDb1D--1N--2S--2N--,3D,game forcing strength; short !D
    1CDb1D--1N--2S--2N--,3H,game forcing strength; short !H
    1CDb1D--1N--2S--2N--,3S,game forcing strength; short !S
    1CDb1D--1N--2S--,3C,Accept transfer with interest in 3NT
    1CDb1D--1N--2S--3C--,3D,game forcing strength; short !D
    1CDb1D--1N--2S--3C--,3H,game forcing strength; short !H
    1CDb1D--1N--2S--3C--,3S,game forcing strength; short !S    
    1CDb1D--1N--,2N,Transfer to diamonds; 6+!D
    1CDb1D--1N--2N--,3C,Not interested in 3NT
    1CDb1D--1N--2N--3C--,3D,correct to !D
    1CDb1D--1N--2N--3C--,3H,game forcing strength; short !H
    1CDb1D--1N--2N--3C--,3S,game forcing strength; short !S
    1CDb1D--1N--2N--,3D,Accept transfer with interest in 3NT
    1CDb1D--1N--2N--3D--,3H,game forcing strength; short !H
    1CDb1D--1N--2N--3D--,3S,game forcing strength; short !S
    1CDb1D--,1H,5+!H
    1CDb1D--,1S,5+!S
    1CDb1D--,2C,5+!C
    1CDb1D--,2D,5+!D
    1CDb1D--,2H,5+!H; 21+ pts
    1CDb1D--,2S,5+!S; 21+ pts
    1CDb1D--,3C,5+!C; 21+ pts
    1CDb1D--,3D,5+!D; 21+ pts

    1CDb----,1N,17-19 pts; balanced
    1CDb----,2N,20-21 pts; balanced
    1CDb----,3N,24-26 pts; balanced
    1CDb----1N--,2C,Stayman; 6+ pts; might not have 4-card major
    1CDb----1N--,2D,Transfer to hearts; 5+!H
    1CDb----1N--,2H,Transfer to spades; 5+!S
    1CDb----1N--,2S,Transfer to clubs; 6+!C
    1CDb----1N--2S--,2N,Not interested in 3NT
    1CDb----1N--2S--2N--,3C,correct to !C
    1CDb----1N--2S--2N--,3D,game forcing strength; short !D
    1CDb----1N--2S--2N--,3H,game forcing strength; short !H
    1CDb----1N--2S--2N--,3S,game forcing strength; short !S
    1CDb----1N--2S--,3C,Accept transfer with interest in 3NT
    1CDb----1N--2S--3C--,3D,game forcing strength; short !D
    1CDb----1N--2S--3C--,3H,game forcing strength; short !H
    1CDb----1N--2S--3C--,3S,game forcing strength; short !S    
    1CDb----1N--,2N,Transfer to diamonds; 6+!D
    1CDb----1N--2N--,3C,Not interested in 3NT
    1CDb----1N--2N--3C--,3D,correct to !D
    1CDb----1N--2N--3C--,3H,game forcing strength; short !H
    1CDb----1N--2N--3C--,3S,game forcing strength; short !S
    1CDb----1N--2N--,3D,Accept transfer with interest in 3NT
    1CDb----1N--2N--3D--,3H,game forcing strength; short !H
    1CDb----1N--2N--3D--,3S,game forcing strength; short !S
    1CDb----,1H,5+!H
    1CDb----,1S,5+!S
    1CDb----,2C,5+!C
    1CDb----,2D,5+!D
    1CDb----,2H,5+!H; 21+ pts
    1CDb----,2S,5+!S; 21+ pts
    1CDb----,3C,5+!C; 21+ pts
    1CDb----,3D,5+!D; 21+ pts
    
    1CDb,2H,4-7 pts; 6+!H
    1CDb,2S,4-7 pts; 6+!S
    1CDb,1H,8+ pts; transfer to spades; 5+!S
    1CDb1H--,1S,accept transfer
    1CDb1H--1S--,1N,0-2 control points (A=2;K=1)
    1CDb1H--1S--,2C,3 control points (A=2;K=1)
    1CDb1H--1S--,2D,4 control points (A=2;K=1)
    1CDb1H--1S--,2H,5 control points (A=2;K=1)
    1CDb,1S,8+ pts; transfer to clubs; 5+!C
    1CDb1S--,2C,accept transfer
    1CDb1S--2C--,2D,0-2 control points (A=2;K=1)
    1CDb1S--2C--,2H,3 control points (A=2;K=1)
    1CDb1S--2C--,2S,4 control points (A=2;K=1)
    1CDb1S--2C--,2N,5 control points (A=2;K=1)
    1CDb,2C,8+ pts; transfer to diamonds; 5+!D
    1CDb2C--,2D,accept transfer
    1CDb2C--2D--,2H,0-2 control points (A=2;K=1)
    1CDb2C--2D--,2S,3 control points (A=2;K=1)
    1CDb2C--2D--,2N,4 control points (A=2;K=1)
    1CDb2C--2D--,3C,5 control points (A=2;K=1)
    1CDb,2D,8+ pts; transfer to hearts; 5+!H
    1CDb2D--,2H,accept transfer
    1CDb2D--2H--,2S,0-2 control points (A=2;K=1)
    1CDb2D--2H--,2N,3 control points (A=2;K=1)
    1CDb2D--2H--,3C,4 control points (A=2;K=1)
    1CDb2D--2H--,3D,5 control points (A=2;K=1)

    1CDb,1N,8-13 pts; balanced; no 5-card suit
    1CDb,2N,14+ pts; balanced; no 5-card suit; forcing to 4NT
    1CDb1N--,2C,Stayman
    1CDb1N--,2D,5+!D
    1CDb1N--,2H,5+!H
    1CDb1N--,2S,5+!S
    1CDb1N--,3C,5+!C
    1CDb1N--,3D,5+!D; slam interest
    1CDb1N--,3H,5+!H; slam interest
    1CDb1N--,3S,5+!S; slam interest
    1CDb1N--,4C,5+!C; slam interest
    1CDb2N--,3C,Stayman
    1CDb2N--,3D,5+!D
    1CDb2N--,3H,5+!H
    1CDb2N--,3S,5+!S
    
    1CDb,3C,4-4-4-1 shape with black singleton; usually less than 12 HCP
    1CDb3C--,3D,artificial;ask partner to clarify singleton
    1CDb3C--3D--,3H,!C singleton
    1CDb3C--3D--,3S,!S singleton
    1CDb,3D,4-4-4-1 shape with red singleton; usually less than 12 HCP
    1CDb3D--,3H,artificial;ask partner to clarify singleton
    1CDb3D--3H--,3S,!D singleton
    1CDb3D--3H--,3N,!H singleton
    1CDb,3H,4-4-4-1 shape with !S singleton; usually 12+ HCP
    1CDb3H--,3S,accepts transfer; asks for control points
    1CDb3H--3S--,3N,4 control points (A=2;K=1)
    1CDb3H--3S--,4C,5 control points (A=2;K=1)
    1CDb3H--3S--,4D,6 control points (A=2;K=1) 
    1CDb,3N,4-4-4-1 shape with !C singleton; usually 12+ HCP
    1CDb3N--,4C,accepts transfer; asks for control points
    1CDb3N--4C--,4D,4 control points (A=2;K=1)
    1CDb3N--4C--,4H,5 control points (A=2;K=1)
    1CDb3N--4C--,4S,6 control points (A=2;K=1)    
    1CDb,4C,4-4-4-1 shape with !D singleton; usually 12+ HCP
    1CDb4C--,4D,accepts transfer; asks for control points
    1CDb4C--4D--,4H,4 control points (A=2;K=1)
    1CDb4C--4D--,4S,5 control points (A=2;K=1)
    1CDb4C--4D--,4N,6 control points (A=2;K=1)
    1CDb,4D,4-4-4-1 shape with !H singleton; usually 12+ HCP
    1CDb4D--,4H,accepts transfer; asks for control points
    1CDb4D--4H--,4S,4 control points (A=2;K=1)
    1CDb4D--4H--,4N,5 control points (A=2;K=1)
    1CDb4D--4H--,5C,6 control points (A=2;K=1)
    1CDb,3S,transfer to 3NT with solid 7-8 card suit
    1CDb3S--,4C,asks for control points
    1CDb3S--4C--,4D,0-2 control points (A=2;K=1)
    1CDb3S--4C--,4H,3 control points (A=2;K=1)
    1CDb3S--4C--,4S,4 control points (A=2;K=1)
    1CDb3S--4C--,4N,5 control points (A=2;K=1)
    1CDb3S--,4D,Which is your suit?
    1CDb3S--4D--,4H,solid !H
    1CDb3S--4D--,4S,solid !S
    1CDb3S--4D--,4N,solid !D
    1CDb3S--4D--,5C,solid !C
    1CDb3S--,4H,5+!H
    1CDb3S--,4S,5+!S

    1D--,2D,inverted minor; 11+ pts; 5+!D
    1D--,3D,preemptive raise in diamonds; 0-7 pts

    1[HS]--,1N,forcing
    1[HS]--,2C,game force; 4+!C
    1[HS]--,2D,game force; 4+!D
    1S--,2H,game force; 5+!H
    ----1[HS]--,2C,3-card invitational support

    2C--,2D,11+ pts; artificial ask for hand description
    2C--,2H,8-10 pts; 5+!H
    2C--,2S,8-10 pts; 5+!S
    2C--,2N,11-12 pts; balanced; no 4-card major
    2C--,3C,Preemptive club raise
    2C--,4C,Preemptive club raise
    2C--,3D,14+ pts; 6+!D
    2C--,3H,14+ pts; 6+!H
    2C--,3S,14+ pts; 6+!S
    2C--,3N,To play
    2C--,4[HS],To play

    2C--2D--,2H,4+!H; 11-13 pts
    2C--2D--,2S,4+!S; 11-13 pts
    2C--2D--,2N,14-15 pts with no 4-card major
    2C--2D--,3C,11-13 pts with no 4-card major
    2C--2D--,3D,4-5!D; 6+!C
    2C--2D--,3H,4+!H; 14-15 pts
    2C--2D--,3S,4+!S; 14-15 pts
    2C--2D--,3N,14-15 pts with solid clubs
    2CDb,Rd,10+ pts and strength in unbid suits
    2C2[DHS],2N,11+ pts; artificial ask for hand description
    2C2[DHS]2N--,3C,11-13 pts
    2C2[DHS]2N--,3D,14-15 pts; 4-5!D; 6+!C
    2C2[DHS]2N--,3H,14-15 pts; 4+!H
    2C2[DHS]2N--,3S,14-15 pts; 4+!S
    2C2D,3D,!D stopper
    2C2H,3H,!H stopper
    2C2S,3S,!S stopper
    2C2[DHS],Db,negative double; 4-card major

    2D--,2[HS],signoff
    2D--,3[CN],signoff
    2D--,4[HS],signoff
    2D--,2N,artificial ask for hand description
    2D--2N--,3C,11-13 pts
    2D--2N--3C--,3D,ask for more info
    2D--2N--3C--3D--,3H,3!S 4!H 1!D 5!C
    2D--2N--3C--3D--,3S,4!S 3!H 1!D 5!C
    2D--2N--3C--3D--,3N,4!S 4!H 0-1!D 4-5!C
    2D--2N--,3D,14-15 pts; 4!S 4!H 1!D 4!C
    2D--2N--,3H,14-15 pts; 3!S 4!H 1!D 5!C
    2D--2N--,3S,14-15 pts; 4!S 3!H 1!D 5!C
    2D--2N--,3N,14-15 pts; 4!S 4!H 0!D 5!C
    2D--2N--3[DHSN]--,4D,artificial ask for control points
    2DDb,Rd,Good diamonds and strength
    2DDb----,Rd,4!H and 4!S
    2DDb----,2H,4!H
    2DDb----,2S,4!S
    2D2[HS],Db,penalty double
    2D2[HS],2N,artificial ask for hand description
    2D2[HS]2N--,3C,11-13 pts
    2D2[HS]2N--3C--,3D,ask for more info
    2D2[HS]2N--3C--3D--,3H,3!S 4!H 1!D 5!C
    2D2[HS]2N--3C--3D--,3S,4!S 3!H 1!D 5!C
    2D2[HS]2N--3C--3D--,3N,4!S 4!H 0-1!D 4-5!C
    2D2[HS]2N--,3D,14-15 pts; 4!S 4!H 1!D 4!C
    2D2[HS]2N--,3H,14-15 pts; 3!S 4!H 1!D 5!C
    2D2[HS]2N--,3S,14-15 pts; 4!S 3!H 1!D 5!C
    2D2[HS]2N--,3N,14-15 pts; 4!S 4!H 0!D 5!C
    2D2[HS]2N--3[DHSN]--,4D,artificial ask for control points

