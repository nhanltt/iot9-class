# Washing machine state

## START
topic:v1cdti/hw/set/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "START"
}

## READY
topic:v1cdti/hw/get/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "READY"
}

## FILLWATER
topic:v1cdti/hw/get/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "FILLING"
}

## HEATWATER
topic:v1cdti/hw/get/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "HEATING"
}

## WASH
topic:v1cdti/hw/get/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "WASHING"
}

## RINSE
topic:v1cdti/hw/get/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "RINSING"
}

## SPIN
topic:v1cdti/hw/get/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "SPINNING"
}

# Operation state

## DOORCLOSE
topic:v1cdti/hw/set/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "DOOR",
    "value"     :   "CLOSED"/"OPENED"
}

## WATERFULLLEVEL
topic:v1cdti/hw/set/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "WATERLEVEL",
    "value"     :   "FULL"
}

## TEMPERATUREREACHED
topic:v1cdti/hw/set/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "TEMPERATURE",
    "value"     :   "REACH"
}


# FAULT state

## TIMEOUT
topic:v1cdti/hw/get/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "FILLWATER_TIMEOUT"/"HEATWATER_TIMEOUT"
}

## OUTOFBALANCE
topic:v1cdti/hw/set/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "OUTOFBALANCE"
}

## MOTORFAILURE
topic:v1cdti/hw/set/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "MOTORFAILED_SPIN"/"MOTOTRFAILED_RINSE"
}

## FAULTCLEARED
topic:v1cdti/hw/set/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "FAULT",
    "value"     :   "CLEARED"
}
