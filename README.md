# BONC移动开发平台文档

## 技术栈

前端技术栈为React、React-Redux、React--Native-Router-Flux、Native-Base

## 功能

* 安全登录登出
* 请求加密
* 版本检测
* 应用安装与卸载
* 聊天功能
* 下载模块
* 用户管理
* 数据持久化

## 项目目录

```
文件夹 PATH 列表
卷序列号为 BC50-A6D0
D:.
│  App.js
│  tree.txt
│  
├─api
│      menus.js
│      
├─components
│  ├─app
│  │      app.png
│  │      index.js
│  │      new.png
│  │      
│  ├─checkbox
│  │      checked.png
│  │      index.js
│  │      uncheck.png
│  │      
│  ├─expand
│  │      down.png
│  │      index.js
│  │      right.png
│  │      top.png
│  │      
│  ├─friend
│  │      index.js
│  │      style.js
│  │      
│  ├─group
│  │      index.js
│  │      style.js
│  │      
│  ├─image
│  │      index.js
│  │      
│  ├─infoItem
│  │      down.png
│  │      horizontal.png
│  │      index.js
│  │      top.png
│  │      
│  ├─input
│  │      index.js
│  │      login_eye_close.png
│  │      login_eye_open.png
│  │      
│  ├─logo
│  │      head.png
│  │      index.js
│  │      logo.png
│  │      user_shadow.png
│  │      
│  ├─menu
│  │      index.js
│  │      menuBack.png
│  │      MenuItem.js
│  │      
│  ├─message
│  │      NoteDetail.js
│  │      NoteItem.js
│  │      PushDetail.js
│  │      PushItem.js
│  │      
│  ├─modalBox
│  │      close.png
│  │      index.js
│  │      
│  ├─org
│  │      Department.js
│  │      departmentStyle.js
│  │      Employee.js
│  │      employeeStyle.js
│  │      index.js
│  │      orgStyle.js
│  │      
│  ├─portalModal
│  │      index.js
│  │      
│  ├─tab
│  │      index.js
│  │      TabItem.js
│  │      
│  ├─titleBar
│  │      back.png
│  │      index.js
│  │      
│  └─toast
│      │  index.js
│      │  Progress.js
│      │  TipsContainer.js
│      │  ToastContainer.js
│      │  
│      └─image
│              tips_error.png
│              tips_success.png
│              tips_warning.png
│              
├─frame
│  │  actionTypes.js
│  │  
│  ├─actions
│  │      index.js
│  │      
│  ├─reducers
│  │      index.js
│  │      reducer.js
│  │      
│  ├─state
│  │      index.js
│  │      state.js
│  │      
│  ├─store
│  │      index.js
│  │      
│  └─style
│          index.js
│          
├─native
│  │  appStore.android.js
│  │  appStore.ios.js
│  │  Ares.common.android.js
│  │  Ares.common.ios.js
│  │  chat.js
│  │  contacts.js
│  │  device.js
│  │  download.js
│  │  index.js
│  │  login.js
│  │  service.js
│  │  store.js
│  │  user.js
│  │  
│  ├─aresNative
│  │      AndroidAppModule.js
│  │      AppStoreModule.js
│  │      ChatModule.js
│  │      ContactsModule.js
│  │      DeviceCheckModule.js
│  │      DownloadModule.js
│  │      HttpModule.js
│  │      LoginModule.js
│  │      UserModule.js
│  │      
│  └─ui
│          AresTextField.js
│          YtImageView.js
│          
├─resources
│  └─img
│          add.png
│          app.png
│          appStore.png
│          app_download.png
│          app_open.png
│          app_update.png
│          barCode.png
│          check.png
│          contacts.png
│          create_group_bg.png
│          defaultImg.png
│          detail.png
│          download.png
│          edit.png
│          email.png
│          employeeOper.png
│          exitApp.png
│          group.png
│          head.png
│          head_lg.png
│          home.png
│          login.jpg
│          login_bg.png
│          login_bg_phone.png
│          login_eye_close.png
│          login_eye_open.png
│          login_logo.png
│          login_pwd.png
│          login_selecte.png
│          login_top.jpg
│          login_unSelecte.png
│          login_user.png
│          menu.png
│          message.png
│          mobile.png
│          modifyPwd.png
│          more.png
│          msgRead.png
│          msgUnread.png
│          next.png
│          note.png
│          noticeSetting.png
│          phone.png
│          pushNote.png
│          right.png
│          search.png
│          selected.png
│          sendMessage.png
│          sign.png
│          sms.png
│          spla.jpg
│          splash.jpg
│          splash.png
│          tabBack.png
│          top_icon_split.png
│          uncheck.png
│          user.png
│          versionCheck.png
│          
├─util
│      AppUtil.js
│      Global.js
│      
└─views
    ├─appDetail
    │      actions.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    ├─appStore
    │      actions.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    ├─assets
    │  │  camera.png
    │  │  drawer-cover.png
    │  │  launchscreen-bg.png
    │  │  logo-kitchen-sink.png
    │  │  logo.png
    │  │  splashscreen.png
    │  │  swiper-1.png
    │  │  swiper-2.png
    │  │  swiper-3.png
    │  │  swiper-4.png
    │  │  web-cover1.jpg
    │  │  
    │  └─contacts
    │          atul.png
    │          himanshu.png
    │          megha.png
    │          pratik.png
    │          sanket.png
    │          sankhadeep.png
    │          saurabh.png
    │          shivraj.jpg
    │          shruti.png
    │          shweta.png
    │          supriya.png
    │          varun.png
    │          
    ├─contacts
    │      actions.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    ├─contactsDetail
    │      actions.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    ├─createGroupOne
    │      actions.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    ├─createGroupTwo
    │      actions.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    ├─groupDetail
    │      actions.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    ├─login
    │      actions.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    ├─main
    │      actions.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    ├─note
    │      actions.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    ├─platform
    │  │  index.js
    │  │  
    │  ├─boot
    │  │      setup.js
    │  │      
    │  ├─screens
    │  │  ├─actionsheet
    │  │  │      icon.js
    │  │  │      index.android.js
    │  │  │      index.ios.js
    │  │  │      regular.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─anatomy
    │  │  │      data.js
    │  │  │      index.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─badge
    │  │  │      index.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─button
    │  │  │      block.js
    │  │  │      custom.js
    │  │  │      default.js
    │  │  │      disabled.js
    │  │  │      full.js
    │  │  │      iconBtn.js
    │  │  │      index.js
    │  │  │      outline.js
    │  │  │      rounded.js
    │  │  │      styles.js
    │  │  │      transparent.js
    │  │  │      
    │  │  ├─card
    │  │  │      basic.js
    │  │  │      card-header-and-footer.js
    │  │  │      card-image.js
    │  │  │      card-list.js
    │  │  │      card-showcase.js
    │  │  │      index.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─checkbox
    │  │  │      index.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─deckswiper
    │  │  │      advanced.js
    │  │  │      index.js
    │  │  │      simple.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─fab
    │  │  │      basic.js
    │  │  │      index.js
    │  │  │      multiple.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─footer
    │  │  │      badgeFooter.js
    │  │  │      basicFooter.js
    │  │  │      iconFooter.js
    │  │  │      iconText.js
    │  │  │      index.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─form
    │  │  │      disabledInput.js
    │  │  │      error.js
    │  │  │      fixedLabel.js
    │  │  │      floatingLabel.js
    │  │  │      iconInput.js
    │  │  │      index.js
    │  │  │      inlineLabel.js
    │  │  │      placeholder.js
    │  │  │      regular.js
    │  │  │      rounded.js
    │  │  │      stacked.js
    │  │  │      styles.js
    │  │  │      success.js
    │  │  │      textArea.js
    │  │  │      underline.js
    │  │  │      
    │  │  ├─Header
    │  │  │      1.js
    │  │  │      2.js
    │  │  │      3.js
    │  │  │      4.js
    │  │  │      5.js
    │  │  │      6.js
    │  │  │      7.js
    │  │  │      8.js
    │  │  │      index.android.js
    │  │  │      index.ios.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─home
    │  │  │      index.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─icon
    │  │  │      basic.js
    │  │  │      index.js
    │  │  │      specific.js
    │  │  │      state.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─layout
    │  │  │      column.js
    │  │  │      customCol.js
    │  │  │      customRow.js
    │  │  │      index.js
    │  │  │      nested.js
    │  │  │      row.js
    │  │  │      
    │  │  ├─list
    │  │  │      basic-list.js
    │  │  │      index.js
    │  │  │      list-avatar.js
    │  │  │      list-divider.js
    │  │  │      list-headers.js
    │  │  │      list-icon.js
    │  │  │      list-separator.js
    │  │  │      list-thumbnail.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─listSwipe
    │  │  │      basic-list-swipe.js
    │  │  │      index.js
    │  │  │      multi-list-swipe.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─loaders
    │  │  │      ProgressBar.android.js
    │  │  │      ProgressBar.ios.js
    │  │  │      Spinner.android.js
    │  │  │      Spinner.ios.js
    │  │  │      
    │  │  ├─picker
    │  │  │      backButtonPicker.js
    │  │  │      customHeaderPicker.js
    │  │  │      headerPicker.js
    │  │  │      headerStylePicker.js
    │  │  │      index.android.js
    │  │  │      index.ios.js
    │  │  │      placeholderPicker.js
    │  │  │      placeholderPickernote.js
    │  │  │      regularPicker.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─radio
    │  │  │      index.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─searchbar
    │  │  │      index.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─segment
    │  │  │      index.js
    │  │  │      SegmentHeader.js
    │  │  │      segmentTab.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─sidebar
    │  │  │      index.js
    │  │  │      style.js
    │  │  │      
    │  │  ├─spinner
    │  │  │      index.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─splashscreen
    │  │  │      index.js
    │  │  │      
    │  │  ├─tab
    │  │  │      basicTab.js
    │  │  │      configTab.js
    │  │  │      index.js
    │  │  │      scrollableTab.js
    │  │  │      styles.js
    │  │  │      tabFive.js
    │  │  │      tabFour.js
    │  │  │      tabOne.js
    │  │  │      tabThree.js
    │  │  │      tabTwo.js
    │  │  │      
    │  │  ├─thumbnail
    │  │  │      index.js
    │  │  │      styles.js
    │  │  │      
    │  │  ├─toast
    │  │  │      index.js
    │  │  │      styles.js
    │  │  │      
    │  │  └─typography
    │  │          index.js
    │  │          styles.js
    │  │          
    │  └─theme
    │      ├─components
    │      │      Badge.js
    │      │      Body.js
    │      │      Button.js
    │      │      Card.js
    │      │      CardItem.js
    │      │      CheckBox.js
    │      │      Container.js
    │      │      Content.js
    │      │      Fab.js
    │      │      Footer.js
    │      │      FooterTab.js
    │      │      Form.js
    │      │      H1.js
    │      │      H2.js
    │      │      H3.js
    │      │      Header.js
    │      │      Icon.js
    │      │      index.js
    │      │      Input.js
    │      │      InputGroup.js
    │      │      Item.js
    │      │      Label.js
    │      │      Left.js
    │      │      ListItem.js
    │      │      Picker.android.js
    │      │      Picker.ios.js
    │      │      Radio.js
    │      │      Right.js
    │      │      Segment.js
    │      │      Separator.js
    │      │      Spinner.js
    │      │      Subtitle.js
    │      │      SwipeRow.js
    │      │      Switch.js
    │      │      Tab.js
    │      │      TabBar.js
    │      │      TabContainer.js
    │      │      TabHeading.js
    │      │      Text.js
    │      │      Textarea.js
    │      │      Thumbnail.js
    │      │      Title.js
    │      │      Toast.js
    │      │      View.js
    │      │      
    │      └─variables
    │              commonColor.js
    │              material.js
    │              platform.js
    │              
    ├─push
    │      actions.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    ├─splash
    │      action.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    ├─user
    │      actions.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    ├─userSetting
    │      actions.js
    │      index.js
    │      reducer.js
    │      state.js
    │      style.js
    │      
    └─webview
            index.js
            

```



