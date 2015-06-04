# WeChat-PHP-SDK

Get request:

    $request = WeChat::get_request();
    $request: Array
    (
        [ToUserName] => gh_8b0f5d25d60x
        [FromUserName] => o4VVEs3f1A3dCrXcXKlpeaduBfM4
        [CreateTime] => 1433321254
        [MsgType] => text
        [Content] => text message.
        [MsgId] => 6156067910799000005
    )

Send response:

    $msg = array(
        'Content' => 'bingo~',
    );
    WeChat::send_response($msg, $request);
