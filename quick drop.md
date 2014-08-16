________


SetKeyDelay, 10, 10 



+q::

loop 4{


loop 6{

random, x, 50,80
sleep, x


MouseClick, right

random, y, 50,80
sleep, y

MouseMove, 0, 35, 2, R

random, m, 50,80
sleep, m

MouseClick, left

random, m, 20,30
sleep, m


}
random, x, 300,700
sleep, x
MouseMove, 40, -210, 20, R

}


return


