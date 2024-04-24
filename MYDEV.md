---
title: my vaex dev
---

```sh
export ENVNAME=newenv
python3 -m virtualenv ${ENVNAME}
cat >>${ENVNAME}/Scripts/activate<<EOF

# Custom Aliases
alias python3='/usr/bin/env python'
alias py='/usr/bin/env python'
EOF

echo "source ${ENVNAME}/Scripts/activate" > activate
source activate

pip install pyreadline3

```