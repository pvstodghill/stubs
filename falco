#! /bin/bash

NAME=$(basename $0)

BASE=$(dirname $0)/..

HOWTO="${BASE}/howto/howto"
HOWTO+=" -q"
HOWTO+=" -T ${BASE}/data/tmp"
HOWTO+=" -f ${BASE}/packages.yaml"


exec ${HOWTO} $NAME "$@"
