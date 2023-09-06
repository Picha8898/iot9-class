# Washing machine state

## START
topic:v1cdti/app/get/6310301031/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "START"
}

## READY
topic:v1cdti/app/get/6310301031/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "READY"
}

## FILLWATER
topic:v1cdti/app/get/6310301031/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "FILLWATER"
}

## HEATWATER
topic:v1cdti/app/get/6310301031/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "HEATWATER"
}

## WASH
topic:v1cdti/app/get/6310301031/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "WASH"
}

## RINSE
topic:v1cdti/app/get/6310301031/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "RINSE"
}

## SPIN
topic:v1cdti/app/get/6310301031/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "SPIN"
}

# Operation state

## DOORCLOSE
topic:v1cdti/app/get/6310301031/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Operation",
    "value"     :   "DOORCLOSE"
}

## WATERFULLLEVEL
topic:v1cdti/app/set/6310301031/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Operation",
    "value"     :   "WATERFULLLEVEL"
}

## TEMPERATUREREACHED
topic:v1cdti/app/set/6310301031/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "Operation",
    "value"     :   "TEMPERATUREREACHED"
}


# FAULT state

## TIMEOUT
topic:v1cdti/app/get/6310301031/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "TIMEOUT"
}

## OUTOFBALANCE
topic:v1cdti/app/set/6310301031/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "OUTOFBALANCE"
}

## MOTORFAILURE
topic:v1cdti/app/set/6310301031/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "MOTORFAILURE"
}

## FAULTCLEARED
topic:v1cdti/app/set/6310301031/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "student_id",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "FAULTCLEARED"
}