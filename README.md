# pro
$conf = array(
	'username' => 'zharmie_pro_official',
	'access_token' => 'YOUR_ACCESS_TOKEN',
	'debugging' => true,
	'like' => array(
		'do' => true,
		'min_likes' => 20,
		'max_likes' => 0
		),
	'follow' => array(
		'do' => true,
		'min_likes' => 50,
		'max_likes' => 0,
		'like_recent' => array(
				'do' => true,
				'count' => 3
			)
		),
	'comment' => array(
		'do' => false,
		'min_likes' => 80,
		'max_likes' => 0
		)
);
