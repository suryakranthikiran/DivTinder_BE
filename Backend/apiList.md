# DevTinder API's

## authRouter

    - POST /signup
    - POST /login
    - POST /logout

## profileRouter

    - GET /profile/view
    - PATCH /profile/edit
    - PATCH /profile/password /forgot password API

## connectionRequestRouter

    - POST /request/send/:status/:userId (status : ignore, intrested)
    - POST /request/review/:status/:requestId ( status : accepted, rejected)

## userRouter

    -GET /user/connections
    -GET //user/requests/received
    -GET /user/feed - Gets you the profile of other users on platform
