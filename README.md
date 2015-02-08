# Munin (node)

## Usage

    docker run --rm --name=munin-node --privileged --net=host -v /:/rootfs:ro -v /proc:/proc:ro -v /sys:/sys:ro ttakezawa/munin-node
