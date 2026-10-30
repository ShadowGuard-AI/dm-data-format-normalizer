![Banner](banner.png)

# dm-data-format-normalizer
Consistently formats data, such as phone numbers or dates, to a predefined standard. This makes identifying true values more difficult by removing distinguishing formatting characteristics that can act as identifiers. Handles data type conversions where necessary for normalization. - Focused on Tools designed to generate or mask sensitive data with realistic-looking but meaningless values

## Install
`git clone https://github.com/ShadowStrikeHQ/dm-data-format-normalizer`

## Usage
`./dm-data-format-normalizer [params]`

## Parameters
- `-h`: Show help message and exit
- `--type`: The type of data to normalize.
- `--input`: The input data to normalize.
- `--input_format`: The input date format (required for date normalization). Example: '%m/%d/%Y'
- `--output_format`: The output date format (default: 
- `--log_level`: Set the logging level (default: INFO)

## License
Copyright (c) ShadowStrikeHQ
