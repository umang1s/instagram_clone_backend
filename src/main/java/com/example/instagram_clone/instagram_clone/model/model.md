# User
    username
    name
    about
    img
    post
    followers
    following
    isPrivate
    isVerfied
    isActive
    themesMode
    email
    mobileNo

# Auth
    username
    password

# Blocked
    username
    time
# Story
    file_url
    type
    id
    start_time
    time

# Filter
    id
    posX
    posY
    rotateX
    rotateY
    rotateZ
    scaleX
    scaleY
    scaleZ
# Post
    id
    username
    time
    about
    location

# React
    username
    reaction_emogies
    timestamp

# Mutual
    message
    id
    public

# Comment
    id
    time
    postid
    username
# ChatUser
    User
    lastMessage
    time
    unseenCount
    id

# Chat
    id
    timestamp
    from
    to
    type
    message
    reaction //reaction emogie
    isSeen

# File
    url
    type
    timestamp
    dimx
    dimy
    
# LoginActivity
    last_login
    address
    device
# Report
    type
    id
    time
    postId
# Contact
    id
    name
    contact
    username
# Public
    //created by User data
    username
    name
    about
    img
    isPrivate
# Activity
    time
    id
    type //comment,tag,follow request,mentions

# PrivacyAndSecurity
    isPrivate
    showActivityStatus
    allowSharing
    photos_of_you : string
    allowMentionsFrom
    HideLikeAndViewCounts
    AllowTagFrom
    requestsFromShops
    deliverRequestFromFollowers
    deliverRequestfromOthers
    whoCanAddYouInGroup
# EmailNotification
    feedbacksEmail
    reminderEmail
    ProductEmail
    NewsEmail
    SupportEmail
# Tag
    List<Post>
# Save
    List<Post>