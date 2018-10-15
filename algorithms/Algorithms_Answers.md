Add your answers to the Algorithms exercises here.
Exercise I:
a.  O(n^c)
b.  O(n**3)
c.  O(n)

Exercise II:
def egg_drop(floors):
    floors = []
    _n_ = len(floors)
    for i in range(1, _n_):
        _f_ = floors[i]
        if i < _f_:
            return true
        else:
            return false

Actually the most efficient solution is to start at the middle floor and check one up and one down.
