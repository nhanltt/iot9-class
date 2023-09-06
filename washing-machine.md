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
    "value"     :   "SPINING"
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
    "name"      :   "STATUS",
    "value"     :   "FILLWATER"/"HEATWATER"
}

## OUTOFBALANCE
topic:v1cdti/hw/get/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "BALANCE"/"IMBALANCE"
}

## MOTORFAILURE
topic:v1cdti/hw/get/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "get",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "NORMAL"/"FAILED"
}

## FAULTCLEARED
topic:v1cdti/hw/set/ุ6310301021/model-01/sn-01
payload: {
    "action"    :   "set",
    "project"   :   "6310301021",
    "model"     :   "model-01",
    "serial"    :   "sn-01",
    "name"      :   "STATUS",
    "value"     :   "CLEARED"/"NOTCLEARED"
}
