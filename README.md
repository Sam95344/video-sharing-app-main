1. Auth API
Sign IN API
localhost:5000/api/auth/signin
{
	"name":"test5",
	"password":"1234"
}
Sign UP API
localhost:5000/api/auth/signup
{
	"name":"test5",
	"email":"test5@gmail.com",
	"password":"1234"
}
2. User/Channel API
update user
localhost:8800/api/users/637343eb0f7b8d2ed2e93ffe
{
	"name":"updated2"
}
delete user
localhost:8800/api/users/637343eb0f7b8d2ed2e93ffe
unsub a channel
localhost:8800/api/users/unsub/63737d7f1fdf7cc8f924573f
sub a channel
localhost:8800/api/users/sub/63737d7f1fdf7cc8f924573f
dislike a video
localhost:8800/api/users/dislike/63737dac1fdf7cc8f9245742
like a video
localhost:5000/api/users/like/63737dce1fdf7cc8f9245745
update view a video
localhost:8800/api/videos/view/63737dce1fdf7cc8f9245745
3. User Find
find a user
localhost:5000/api/users/find/63737d7f1fdf7cc8f924573f
4. Comments
Get all comments
localhost:8800/api/comments/63737d7f1fdf7cc8f924573f
add comment a video
localhost:8800/api/comments
{
	"desc":"third comment ",
	"videoId":"63737d7f1fdf7cc8f924573f"
}
5. Videos
trending videos
localhost:5000/api/videos/trend
get single video
localhost:5000/api/videos/find/63737d7f1fdf7cc8f924573f
get by query search
localhost:8800/api/videos/search?q=2nd
get by tags
localhost:8800/api/videos/tags?tags=py
get random video
localhost:5000/api/videos/random
subscribed channel video
localhost:5000/api/videos/sub
add a video
localhost:8800/api/videos
{
	"title":"the best video from 3rd user",
	"desc":"test desc",
	"imgUrl":"test",
	"videoUrl":"test"
}
Videos API



User/Channel API



Comments API



Auth API

