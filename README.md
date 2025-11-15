# Article Limit - Plugin for Joomla

Plugin for Joomla that controls the number of articles Authors can create.

## ⚠️ Important Disclaimer

**WARNING: USE AT YOUR OWN RISK**

I do not take any responsibility for:
- Data loss or corruption
- Website malfunctions or downtime  
- Security vulnerabilities
- Any other issues that may arise from using this plugin

**ALWAYS TEST ON A STAGING/DEVELOPMENT ENVIRONMENT FIRST** before deploying to your production website. Make sure to:
- Create full backups of your website and database
- Test all functionality thoroughly
- Verify compatibility with your Joomla version and other extensions

## 📋 Description

Article Limit is a Joomla plugin that allows administrators to set article creation limits for **Authors only**. It prevents Authors from exceeding their allocated article quotas while providing clear feedback about their current usage.

## ✨ Features

- **Author-only limits** - Set article limits specifically for Authors (group ID: 3)
- **Flexible configuration** - Limit can be disabled (0 = unlimited)
- **Category filtering** - Exclude specific categories from limit calculations
- **Article state control** - Choose which article states count toward the limit (published, unpublished, archived)
- **Admin protection** - Super Users and Administrators have unlimited article creation
- **User feedback** - Authors see their current article count when creating new articles
- **Frontend & Backend** - Works in both administrator and site interfaces

## 🚀 Installation

1. Download the latest release ZIP file
2. Install through Joomla Administrator → Extensions → Manage → Install
3. Enable the plugin in → Extensions → Plugins → Search for "Article Limit"

## ⚙️ Configuration

After installation, configure the plugin through:  
**Extensions → Plugins → Search "Article Limit"**

### Available Settings:

- **Author Limit** - Maximum articles for Authors (group ID: 3)
- **Exclude Categories** - Categories that won't count toward the limit
- **Count Article States** - Which article states to include in limit calculations

### Limit Values:
- **0** = Unlimited articles
- **>0** = Maximum number of articles allowed

## 🎯 How It Works

1. When an Author tries to create a new article, the plugin checks their article count
2. It calculates how many articles they've already created
3. If the Author exceeds their limit, article creation is blocked
4. Authors see informative messages about their current article count


