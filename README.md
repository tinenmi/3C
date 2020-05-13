# 3C

func Data@Array { (Data } reduce add { 0) } `sum

func (@, `Start, @empty) { Start } def reduce
func (`f, `Start, `Data@Array) { f ((Data::(1..) } reduce f { Start)) { Data@0 } def reduce
