# osu-mapping-helping
codes for osu mapping

##hour/mins/sec/milliseconds to milliseconds

def min_sec_to_sec(x, y):
    return str(x*60 + y) + '   ' + f'{x} {y}'

def min_sec_milisec_to_milisec(x, y, z):
    return str(x*60*1000 + y*1000 + z) + '   ' + f'{x} {y} {z}'

def hour_min_sec_milisec_to_milisec(x, y, z, w):
    return str(x*60*1000*60 + y*60*1000 + z*1000 + w) + '   ' + f'{x} {y} {z} {w}'
