playbook-grafana-on-influxdb-for-centos
---------------------------------------

Will be install of the grafana and influxdb on the CentOS.

# Prerequired

- [ansible](http://www.ansible.com/)
- [packer](http://www.packer.io/)
- [vagrant](http://www.vagrantup.com/)
- [virtualbox](https://www.virtualbox.org/)

How to setup?
-------------

# Setup of required package on the Mac OS X

```
> brew bundle
```

# Deploy on vagrant box

```
> vagrant up --provision
```

# A list of references.

- [Grafana on InfluxDB をちょっとだけ触ってみた](http://qiita.com/sonots/items/8fbc92ff1c3e57ee7de7)
- [InfluxDB と fluentd を組み合わせを試してみた](http://qiita.com/hakobera/items/fbe7669a1c2b763bcd8d)
- [InfluxDBとGrafanaとfluentdで、twitterデータのリアルタイム集計・可視化](http://qiita.com/ixixi/items/a56ea15b582c7f014a57)
- [InfluxDB試してみた](http://qiita.com/chobie@github/items/c8220d9352df90963862)

# License

MIT.