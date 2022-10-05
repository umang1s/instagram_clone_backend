url=https://www.instagram.com/

# url
    List<Story> getStory()
    List<Post> getPost()
    User getUser()
    List<User> getSuggestions(5)
    bool unfollow(User)
    bool follow(User)
    bool addToFavorite(Post)
    bool reportPost(Post)
    bool deletePost(Post)
    bool addToBookmarks(Post)
    List<User> likeOnPost(Post)
    List<Comment> commentsOnPost(Post)
    int countLikeOnPost(Post)
    int countCommentsOnPost(Post)

# url/inbox
    List<ChatUser> getChatUserList()
    List<Chat> getChats(User)
    bool deleteChatUser(User)
    Chat addChat(Message,User)
    List<Chat> getLatestChat(Chat,User) //older chat
    bool deleteChat(Chat)
    bool modifyChat(Chat)
    bool requestCall(User,type)
    bool abortCall(User)
    bool blockUser(User)
    bool unblockUser(User)
    bool muteMessage(User)
    bool unMuteMessage(User)
    bool muteCall(User)
    bool unMuteCall(User)
    bool getMuteMessageStatus(User)
    bool getMuteCallStatus(User)
    bool likeChat(Chat)
    bool unLikeChat(Chat)
    String uploadDocument(File)
    int lastSeen(User)
    List<LoginActivity> getLoginActivity()
    List<Notification> getNotification()
    bool reportAProblem(Problem)
    User updateUser(User)
    bool checkUserName(String)
    bool temporaryDisableAccount()
    bool switchToProfessional()
    String changePassword(String,String) //old password,new password
    EmailNotification getEmailNotification()
    EmailNotification updateEmailNotification()
    PushNotification getPushNotification()
    PushNotification updatePushNotification()
    List<Contact> getMyContact()
    List<Contact> removeFromContact(Contact)
    bool deleteAllContact()
    PrivacyAndSecurity getMyPrivacyAndSecurity()
    PrivacyAndSecurity updateMyPrivacryAndSecurity()

    
# url/post
    Post createPost(Post)


# url/search
    List<Public> getSearchResult(String)

# url/explore
    List<Post> getExplore()
    List<PostThumnails>

# url/activity 
    List<Activity> getActivity() //types request,like,comment..

# url/user
    List<Post> getMyPost()
    List<Save> getSaved()
    List<Tag> getMyTagged()
    bool deleteSaved(Saved)
    bool deleteTagged(Tag)
    bool addTagged(Tag)
    bool addSaved(Saved)

    void handleAccessDenied()
# url/saved

# url/setting

# url/logout

# url/login

# url/signup

# url/forgot_password

# url/reset_password

# url/public/about

# url/public/help

# url/public/press 

# url/public/api

# url/public/jobs

# url/public/privacy/

# url/public/terms/

# url/public/locations/