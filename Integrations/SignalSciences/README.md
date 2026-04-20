
# SignalSciences

Integration for SignalSciences

Python Version - V3_11
#### Parameters
|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|API Root|The base API root URL for Signal Sciences.|True|String||
|Email|The email address associated with the Signal Sciences account.|True|String||
|API Token|The API token used for authentication with Signal Sciences.|True|Password||
|Corporation Name|The unique name of the organization or corporation context as defined in Signal Sciences.|True|String||
|Verify SSL|If selected, the integration validates the SSL certificate when connecting to the Signal Sciences server.|False|Boolean||


#### Dependencies
| |
|-|
|requests-2.32.5-py3-none-any.whl|
|pyparsing-3.3.2-py3-none-any.whl|
|httpx-0.28.1-py3-none-any.whl|
|rsa-4.9.1-py3-none-any.whl|
|proto_plus-1.27.1-py3-none-any.whl|
|uritemplate-4.2.0-py3-none-any.whl|
|EnvironmentCommon-1.0.3-py3-none-any.whl|
|certifi-2026.2.25-py3-none-any.whl|
|cffi-2.0.0-cp311-cp311-manylinux2014_x86_64.manylinux_2_17_x86_64.whl|
|pyopenssl-25.3.0-py3-none-any.whl|
|TIPCommon-2.3.4-py3-none-any.whl|
|typing_extensions-4.15.0-py3-none-any.whl|
|pyasn1-0.6.2-py3-none-any.whl|
|cryptography-46.0.5-cp311-abi3-manylinux2014_x86_64.manylinux_2_17_x86_64.whl|
|httpcore-1.0.9-py3-none-any.whl|
|google_auth_httplib2-0.3.0-py3-none-any.whl|
|charset_normalizer-3.4.5-cp311-cp311-manylinux2014_x86_64.manylinux_2_17_x86_64.manylinux_2_28_x86_64.whl|
|idna-3.11-py3-none-any.whl|
|httplib2-0.31.2-py3-none-any.whl|
|urllib3-2.6.3-py3-none-any.whl|
|protobuf-6.33.5-py3-none-any.whl|
|pycryptodome-3.23.0-cp37-abi3-manylinux_2_17_x86_64.manylinux2014_x86_64.whl|
|requests_toolbelt-1.0.0-py2.py3-none-any.whl|
|pycparser-3.0-py3-none-any.whl|
|google_auth-2.47.0-py3-none-any.whl|
|h11-0.16.0-py3-none-any.whl|
|anyio-4.12.1-py3-none-any.whl|
|googleapis_common_protos-1.73.0-py3-none-any.whl|
|pyasn1_modules-0.4.2-py3-none-any.whl|
|google_api_core-2.30.0-py3-none-any.whl|
|google_api_python_client-2.188.0-py3-none-any.whl|


## Actions
#### Add IP to Block List
Use the **Add IP to Block List** action to add a specific IP address to the block list of a designated site. Supported Entities: IP address.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Site Name|The API name of the site as defined in the Signal Sciences dashboard.|True|None||
|IP Address|A comma-separated list of IP addresses to add to the Signal Sciences block list.|False|None||
|Note|The descriptive note or justification associated with the blocked IP address.\nThis field is mandatory for the Signal Sciences API.|True|None||



#### Ping
Use the **Ping** action to test the connectivity to Signal Sciences.
Timeout - 600 Seconds



#### Remove IP from Block List
Use the **Remove IP from Block List** action to remove a specific IP address from the block list of a designated site. Supported Entities: IP address.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Site Name|The API name of the site as defined in the Signal Sciences dashboard.|True|None||
|IP Address|A comma-separated list of IP addresses to remove from the Signal Sciences block list.|False|None||



#### List Sites
Use the **List Sites** action to retrieve a list of all sites available within the corporation in Signal Sciences.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Max Sites To Return|The maximum number of sites to return.Setting this value to 0 or leaving it empty returns all available sites.|False|None||



#### Remove IP from Allow List
Use the **Remove IP from Allow List** action to remove a specific IP address from the allow list of a designated site. Supported Entities: IP address.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Site Name|The API name of the site as defined in the Signal Sciences dashboard.|True|None||
|IP Address|A comma-separated list of IP addresses to remove from the Signal Sciences allow list.|False|None||



#### Add IP to Allow List
Adds an IP address to the Allow List for a specific Site. Supported Entities: IP address.
Timeout - 600 Seconds


|Name|Description|IsMandatory|Type|DefaultValue|
|----|-----------|-----------|----|------------|
|Site Name|The API name of the site as defined in the Signal Sciences dashboard.|True|None||
|IP Address|A comma-separated list of IP addresses to add to the Signal Sciences allow list.|False|None||
|Note|The descriptive note or justification associated with the allowed IP address.\nThis field is mandatory for the Signal Sciences API.|True|None||









