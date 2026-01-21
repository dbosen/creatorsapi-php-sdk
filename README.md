# Creators API PHP SDK

This is a fork of the Amazon CreatorsAPI PHP SDK. I uploaded it to github and packagist to be able to require it with composer. 
This fork does not contain any changes compared to the official Amazon zip file - besides these obvious changes in the readme.

## Prerequisites

### PHP Version Support
- **Supported**: To run the SDK you need PHP version 8.1 or higher.

## Setup Instructions

### 1. Install and Configure PHP

For PHP installation, you can download it from the official website: https://www.php.net/downloads

```bash
# Check PHP version
php --version
```

### 2. Install
```bash
composer require dbosen/creatorsapi-php-sdk
```

### 3. Run Sample Code
Navigate to the examples directory to run the samples.

```bash
cd vendor/dbosen/creatorsapi-php-sdk/examples
```

Before running the samples, you'll need to configure your API credentials in the sample files by replacing the following placeholders:

- `<YOUR CREDENTIAL ID>` - Your API credential ID
- `<YOUR CREDENTIAL SECRET>` - Your API credential secret  
- `<YOUR CREDENTIAL VERSION>` - Your credential version (e.g., "2.1" for NA, "2.2" for EU, "2.3" for FE region)
- `<YOUR MARKETPLACE>` - Your marketplace (e.g., "www.amazon.com" for US marketplace)
- `<YOUR PARTNER TAG>` - Add valid Partner Tag for the requested marketplace in applicable sample code snippet files

Run the following commands to run the sample files:

**Get detailed product information:**
```bash
php SampleGetItems.php
```

**Search for products:**
```bash
php SampleSearchItems.php
```

#### Other Samples
Check the `examples` directory for additional sample files with various API operations.
