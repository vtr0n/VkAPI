# VkAPI
The PHP class for VK API 
### Usage
```
$vk = new VkAPI;
$vk->access_token = TOKEN;
$vk->messages_send($user_id = 1, $chat_id = '', $message = 'Durov, you banned!');
$vk->account_ban_user($user_id = 1);
```