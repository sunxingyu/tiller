# Random Plugin
If you add `random` to your list of data sources in `common.yaml`, you'll be able to use randomly-generated values and strings in your templates, e.g. `<%= random_uuid %>`. This may be useful for generating random UUIDs, server IDs and so on. An example hash with demonstration values is as follows :

	{"random_base64"=>"nubFDEz2MWlIiJKUOQ+Ttw==",
	 "random_hex"=>"550de401ef69d92b250ce379e5a5957c",
	 "random_bytes"=>"3»fS`\W IFïü8.ß",
	 "random_number_10"=>8,
	 "random_number_100"=>71,
	 "random_number_1000"=>154,
	 "random_urlsafe_base64"=>"MU9UP8lEOVA3Nsb0OURkrw",
	 "random_uuid"=>"147acac8-7229-44af-80c1-246cf08910f5"}
