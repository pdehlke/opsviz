source "https://supermarket.getchef.com"

# Community Cookbooks
cookbook 'elasticsearch'
cookbook 'kibana'
cookbook 'logstash', git: 'https://github.com/foxycoder/chef-logstash.git'

# Our Cookbooks
cookbook 'rabbitmq_cluster', path: './site-cookbooks/rabbitmq_cluster'
cookbook 'bb_elasticsearch', path: './site-cookbooks/bb_elasticsearch'
cookbook 'bb_monitor', path: './site-cookbooks/bb_monitor'

# Override opsworks to use community apache2
cookbook 'apache2', path: './apache2'
