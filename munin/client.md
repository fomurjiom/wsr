apt install munin-node munin-plugins-extra rrdtool

cat <<EOF >> /etc/munin/munin-node.conf
cidr_allow 192.168.1.0/24
cidr_allow 192.168.0.0/24
EOF
