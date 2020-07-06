# Stunnel

This Ansible role is a simple way to setup stunnel server.

## Role variables

* ```stunnel_forward_port``` - where stunnel traffic will be redirected
* ```stunnel_listen_port``` - which port the stunnel server will accept traffic from
* ```stunnel_listen_cert``` - default stunnel crt file, usually /etc/stunnel/stunnel.crt
* ```stunnel_listen_key``` - default stunnel key file, usually /etc/stunnel/stunnel.key

## License

MIT
