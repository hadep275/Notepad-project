# Notepad Web Application

## Overview

This is a simple Notepad web application that allows users to create and edit text notes in a web browser. The application provides a basic user interface with essential features such as a resizable window, minimize, and close buttons. It is built using HTML, CSS, and does not require any backend server.
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
<meta name="viewport" content="width=device-width">
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
<title>Loom | Free Screen &amp; Video Recording Software | Loom</title>
<!-- Cookie banner only available on marketing site for now. -->
<!-- Likely to be reenabled once ready to rollout onto webapp-client -->
<!-- <script type="text/javascript">
  (function () {
    fetch('https://location.loom.com', {
      method: 'GET',
    })
      .then(response => {
        const targetCountries = [];
        const userCountry = response.headers.get('x-loom-country');

        if (targetCountries.includes(userCountry)) {
          const head = document.getElementsByTagName('head')[0];
          const js = document.createElement('script');

          js.type = 'text/javascript';
          js.src =
            'https://cmp.osano.com/AzytdUSlZ32371fP0/ba69bebe-a167-497d-9119-634931398b23/osano.js';

          head.append(js);
        }
      })
      .catch(() => {});
  })();
</script>
 -->


<meta name="slack-app-id" content="A9G1TH4S2">

<!-- SEO -->
<meta name="application-name" content="Loom" />
  <meta name="description" content="Use Loom to record quick videos of your screen and cam. Explain anything clearly and easily – and skip the meeting. An essential tool for hybrid workplaces." />

  <!-- open graph and twitter tags -->
    <meta property="og:site_name" content="Loom">
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://www.loom.com">
  <meta property="og:title" content="Loom | Free Screen &amp; Video Recording Software">
      <meta property="og:description" content="Use Loom to record quick videos of your screen and cam. Explain anything clearly and easily – and skip the meeting. An essential tool for hybrid workplaces." />
    <meta property="og:image" content="https://cdn.loom.com/assets/img/og/loom-banner.png">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="600">
  <meta name="twitter:card" content="summary_large_image" />




<!-- Web App Icons -->
<meta name="application-name" content="Loom">
<meta name="mobile-web-app-capable" content="yes">
<meta name="theme-color" content="#ffffff">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="Loom">
<meta name="msapplication-TileColor" content="#b91d47">
<meta name="msapplication-TileImage" content="https://cdn.loom.com/assets/favicons-loom/mstile-150x150.png">

<link rel="icon" href="https://cdn.loom.com/assets/favicons-loom/favicon.ico" sizes="any">
<link rel="icon" href="https://cdn.loom.com/assets/favicons-loom/favicon.svg" type="image/svg+xml">
<link rel="icon" type="image/png" sizes="32x32" href="https://cdn.loom.com/assets/favicons-loom/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="192x192" href="https://cdn.loom.com/assets/favicons-loom/android-chrome-192x192.png">
<link rel="apple-touch-icon" sizes="180x180" href="https://cdn.loom.com/assets/favicons-loom/apple-touch-icon-180x180.png">
<link rel="mask-icon" color="#625df5" href="https://cdn.loom.com/assets/favicons-loom/safari-pinned-tab.svg">


  <link rel="stylesheet" href="https://cdn.loom.com/assets/css/8030-668ce173d86bd0700a80.css" />

  <link rel="stylesheet" href="https://cdn.loom.com/assets/css/1487-ac82462a2ca5c31235c0.css" />


<script>
  window._LOOM_ = "%7O%22OVYYVAT_ERPNCGPUN_FVGR_XRL%22%3N%226Yq-a7bHNNNNNWKXybyTXC7sCMus-WzaKnlg9CA5%22%2P%22PUEBZR_RKGRAFVBA_VQ%22%3N%22yvrpoqqzxvvvuarqbozyzvyyubqwxqzo%22%2P%22PYVRAG_YBT_YRIRY%22%3N%22sngny%2Preebe%2Pjnea%2Pvasb%22%2P%22PYBHQSEBAG_HEV%22%3N%22pqa.ybbz.pbz%22%2P%22NIFREIRE_PYBHQSEBAG_HEV%22%3N%22yhan.ybbz.pbz%22%2P%22RYRIVB_NPPBHAG_VQ%22%3N%225p7qp041087r9%22%2P%22TBBTYR_NCV_PYVRAG_VQ%22%3N%22443240113960-6zw529e3e24tcc4p9h57a9aqet01v911.nccf.tbbtyrhfrepbagrag.pbz%22%2P%22YBBZ_QRFXGBC_CEBGBPBY%22%3N%22ybbzQrfxgbc%3N%2S%2S%22%2P%22ZHK_RAI_XRL%22%3N%229ntt7cyq771c850zs45zfatc3%22%2P%22CHFU_FREIRE_CHOYVP_XRL%22%3N%22OSMAlOrBig4yrVK8OhRu7u2-7lFWCL2bSfWdV5HyfTxa57ZKc924pqoufgdF69Uz-IYo1wXEEm4LnRu7qTeFKFZ%22%2P%22FGEVCR_CHOYVP_XRL%22%3N%22cx_yvir_ZT87GpsZRyPHEEBsexfSFZ8k%22%2P%22QNGNQBT_EHZ_NCCYVPNGVBA_VQ%22%3N%227ns92855-r997-4q9o-nn41-839r1p64r6s3%22%2P%22QNGNQBT_EHZ_PYVRAG_GBXRA%22%3N%22choo1955571qp736r541o72313p6942242s%22%2P%22QNGNQBT_EHZ_RANOYR%22%3N%22gehr%22%2P%22QNGNQBT_EHZ_FREIVPR%22%3N%22ybbz-cebq%22%2P%22QNGNQBT_EHZ_FRFFVBA_FNZCYR_ENGR%22%3N%2215%22%2P%22QNGNQBT_EHZ_FRFFVBA_ERCYNL_FNZCYR_ENGR%22%3N%2215%22%2P%22QNGNQBT_YBT_PYVRAG_GBXRA%22%3N%22cho6n5r653719oonqp7o8q28o628o09oq41%22%2P%22QNGNQBT_YBT_RANOYR%22%3N%22gehr%22%2P%22QNGNQBT_YBT_FNZCYR_ENGR%22%3N%2210%22%2P%22QNGNQBT_YBT_FREIVPR%22%3N%22jroncc%22%2P%22YBBZ_FQX_NCV_XRL%22%3N%22677no500-qo70-4087-91ns-6rsqo06sss68%22%2P%22PNAAL_VB_NCC_VQ%22%3N%2258n6799q8q61o9968qnq922n%22%2P%22PBURER_PYVRAG_XRL%22%3N%22J-YswQFDvvMv-ud7T761GKB1%22%2P%22CNPXNTRF_PYBHQSEBAG_HEV%22%3N%22cnpxntrf.ybbz.pbz%22%2P%22FRAGEL_ERCYNLF_BA_REEBE_FNZCYR_ENGR%22%3N%220.001%22%2P%22SO_NCC_VQ%22%3N%221591221991190878%22%2P%22NABA_PBBXVR_QBZNVA%22%3N%22ybbz.pbz%22%2P%22YBBZ_ONER_HEV%22%3N%22ybbz.pbz%22%2P%22YBBZ_HEV%22%3N%22jjj.ybbz.pbz%22%2P%22ABQR_RAI%22%3N%22cebqhpgvba%22%2P%22YBBZ_IREFVBA%22%3N%22o5o72rs%22%2P%22YBBZ_ERPBEQ_JF_HEV%22%3N%22erpbeq.ybbz.pbz%22%7Q";


  window.loomSSRUser = {"triggers":{"desktop_stop_rec_tooltip":{"show":false,"complete":false},"education_user_upgraded_modal":{"show":true,"complete":false},"email_verified":{"show":false,"complete":false},"gmail_integration_share_page_upsell":{"show":false,"complete":false},"new_transcript_experience_owner":{"show":true,"complete":false},"new_transcript_experience_viewer":{"show":true,"complete":false},"request_push_permissions":{"show":true,"complete":false},"show_avatar_tooltip":{"show":true,"complete":false},"show_data_retention_warning":{"show":true,"complete":false},"show_download_video_info_modal":{"complete":true,"show":false},"show_get_started_checklist":{"complete":true,"show":false},"show_milestone_post_recording_celebration":{"show":false,"complete":true},"show_mobile_banner_prompt":{"show":true,"complete":false},"website_show_new_get_started_checklist_banner":{"show":false,"complete":false}},"has_activated_desktop_app":false,"has_activated_chrome_extension":true,"has_activated_ios_app":false,"has_activated_android_app":false,"cacheVersion":1,"id":27438474,"avatars":[{"name":"a315da7d4afd45439bb292c88f1a5412","large":"avatars/27438474_a315da7d4afd45439bb292c88f1a5412_1024.jpg","thumb":"avatars/27438474_a315da7d4afd45439bb292c88f1a5412_192.jpg"}],"basic_video_limit":25,"email":"1.2.3.4.jobbs@gmail.com","first_name":"1234","last_name":null,"role":"client","is_primary":true,"company_name":null,"deletion_pending":null,"help_options":null,"tour_settings":null,"company_position":null,"status":"verified","oauth":{"google":{"id":"115175470858870376301","medium":"google","email":"1.2.3.4.jobbs@gmail.com","team_id":null,"team_name":null,"team_domain":null,"external_avatar":"https://lh3.googleusercontent.com/a/ACg8ocJiroh6tXue-8ysXV9XKj3ZhRs4OQ01oVQFTTtkIIGk=s1024-c","createdAt":"2024-01-26T02:37:28.589Z","updatedAt":"2024-01-26T02:37:28.589Z"}},"capabilities":{},"push_subscriptions":{"subscriptions":{}},"trial_status":null,"checklist":{"has_viewed_videos":true,"complete_onboarding":true,"first_video_recording":true},"num_credits":0,"recorder_settings":{},"tours":{},"notification_settings":{"video_read":true,"share_video":true,"push_video_read":false,"push_share_video":true,"push_reshare_video":true,"push_video_comments":false,"push_weekly_digests":false,"all_comments_enabled":true,"push_comment_replies":false,"push_video_reactions":false,"push_video_privacy_changed":true},"video_settings":{"use_gif":true,"use_emojis":true},"last_country":null,"integration_settings":{"integrate_jira":{"expand":true,"enabled":true},"integrate_gmail":{"expand":true,"enabled":true},"integrate_github":{"expand":true,"enabled":true},"integrate_gitlab":{"expand":true,"enabled":true},"integrate_dropbox":{"expand":true,"enabled":true},"integrate_intercom":{"expand":true,"enabled":true},"integrate_invision":{"expand":true,"enabled":true},"integrate_confluence":{"expand":true,"enabled":true},"integrate_salesforce":{"expand":true,"enabled":true},"integrate_google_docs":{"expand":true,"enabled":true},"integrate_hacker_news":{"expand":true,"enabled":true},"integrate_producthunt":{"expand":true,"enabled":true},"integrate_salesforce_iq":{"expand":true,"enabled":true}},"app_settings":{"sidebar_hidden":false},"timezone_offset":0,"persona":{"persona_v1":{"role":null,"company":null,"complete":true,"use_cases":[],"company_size":null,"use_case_plan":"personal","education_type":null,"other_use_case":null,"company_industry":null,"company_size_exact":null,"use_case_plan_persona":"For personal projects"}},"jtbd":{"deleted":false,"watched":[],"archived":false},"invite_counts":{},"onboarding":{},"email_change_count":0,"user_identity_id":"27366850","account_type":"team","tags":{},"default_workspace_id":"27875370","referrer_partner_id":null,"terms_accepted":true,"terms_accepted_created_at":"2024-01-26T02:37:28.483Z","createdAt":"2024-01-26T02:37:28.484Z","updatedAt":"2024-01-26T02:56:47.885Z","deletedAt":null,"selected_workspace_id":27875370,"is_sdk_shared_user":false,"has_gmail_account":true,"hasGmailAccount":true,"hasWebPushSubscription":false,"password_is_set":false,"scopes":["ACCOUNT_NOTIFICATIONS","AUTHENTICATED_USER_ACCESS","AUTOJOIN_SIDEBAR","BLUR_ACCESS","CONTENT_UPLOAD_ACTION_READ","CONTENT_UPLOAD_ACTION_WRITE","CREATE_SPACE","CUSTOM_BRANDING_ACCESS","ENGAGEMENT_INSIGHTS_ACCESS","ENGAGEMENT_INSIGHTS_ADMIN_ACCESS","ENGAGEMENT_INSIGHTS_CSV_ACCESS","FAVORITES","FILLER_WORD_REMOVAL_V1","HELP_BUBBLE_CONTACT_SUPPORT","IMAGE_CAPTURE_ACCESS","IMAGE_CTA_ACCESS","IMAGE_EDIT_OPTIONS_ACCESS","IMAGE_ENHANCED_CAPTURE_ACCESS","IMAGE_PASSWORD_PROTECT_ACTION","IMAGE_SETTINGS_ACCESS","IMAGE_SHARE_PRIVATE_ACTION","IMAGE_SHARE_WITH_TEAM_ACTION","IMAGE_TOOLS_ACCESS","INVITE_ADMIN_ACTION","INVITE_CREATOR_ACTION","INVITE_CREATOR_LITE_ACTION","MEMBERS_PAGE_CSV_DOWNLOAD","PASSWORD_RESET_ACTION","PERSONAL_ARCHIVE_READ","PERSONAL_ARCHIVE_WRITE","PERSONAL_LIBRARY_READ","PERSONAL_LIBRARY_WRITE","RECORDER_BROWSER_EXTENSION_ACCESS","RECORDING_TIMER_PAYWALL_LITE","RESEND_INVITE_ACTION","SEARCH_ACCESS","SUGGESTED_WORKSPACE_BANNER","SUGGESTED_WORKSPACE_SIDEBAR","SUGGESTED_WORKSPACE_WORKSPACE_SWITCHER","TEAM_ARCHIVE_READ","TEAM_ARCHIVE_WRITE","TEAM_LIBRARY_READ","TEAM_LIBRARY_WRITE","TRANSCRIPT_SEARCH_ACCESS","TRANSCRIPTION_ACCESS","UNLIMITED_CREATORS","UNLIMITED_VIEWERS","USER_STATE_WRITE","VIDEO_COMMUNITY_PUBLISH_ACCESS","VIDEO_CTA_ACCESS","VIDEO_DOWNLOAD_ACCESS","VIDEO_EDIT_BY_TRANSCRIPT_ACCESS","VIDEO_EDIT_OPTIONS_ACCESS","VIDEO_ENHANCED_RECORDER_ACCESS","VIDEO_GUEST_DELETE_ACCESS","VIDEO_PASSWORD_PROTECT_ACTION","VIDEO_PUBLISH_ACCESS","VIDEO_RECORD_ACCESS","VIDEO_SETTINGS_ACCESS","VIDEO_SHARE_PRIVATE_ACTION","VIDEO_THUMBNAIL_ACCESS","VIDEO_TOOLS_ACCESS","VIDEO_TRIM_ACCESS","VIDEO_WEAVE_ACCESS","VIEW_CREATE_SPACE","VIEW_SPACES_ONBOARDING_TOUR","WATCH_LATER","WORKSPACE_ADMIN_INSIGHTS_TAB","WORKSPACE_APPEARANCE_READ","WORKSPACE_APPEARANCE_WRITE","WORKSPACE_BILLING_ACCESS","WORKSPACE_CONTACT_IMPORT_INTEGRATION_READ","WORKSPACE_CONTACT_IMPORT_INTEGRATION_WRITE","WORKSPACE_DOMAIN_JOIN_MANAGE","WORKSPACE_GENERAL_ACCESS","WORKSPACE_INVITATIONS_CONTROL","WORKSPACE_PRIVACY_ACCESS","WORKSPACE_PRIVACY_PAYWALL","WORKSPACE_SSO_READ","WORKSPACE_ZOOM_INTEGRATION_READ","WORKSPACE_ZOOM_INTEGRATION_WRITE"],"availableFtux":[{"name":"global_limit_banner","priority":0},{"name":"member_video_limit_banner","priority":0},{"name":"workspace_content_limit_banner","priority":0},{"name":"recorder_download_banner","priority":1},{"name":"creator_lite_member_limit_banner","priority":0},{"name":"approaching_limit_banner","priority":1},{"name":"mobile_download_banner","priority":1},{"name":"member_video_threshold_banner","priority":1},{"name":"web_permissions_banner","priority":1},{"name":"data_retention_banner","priority":1},{"name":"synced_meetings_ftux_banner","priority":1},{"name":"global_admin_dunning_banner","priority":0},{"name":"global_admin_payment_authentication_banner","priority":0},{"name":"global_remediation_banner","priority":0},{"name":"loom_ai_addon_ftux","priority":0},{"name":"loom_ai_trial_ended_ftux","priority":0},{"name":"auto_chapters_ftux","priority":0},{"name":"trim_by_transcript_ftux","priority":0},{"name":"trim_by_transcript_share_page_ftux","priority":2},{"name":"pnp_update_sept_2023","priority":0},{"name":"email_gating_ftux","priority":0},{"name":"creator_salesforce_engagement_tracking_ftux","priority":0},{"name":"admin_salesforce_settings_ftux","priority":1},{"name":"pnp_update_nov_2023","priority":0},{"name":"eoy_2023_ftux","priority":1},{"name":"title_variables_ftux","priority":1},{"name":"incentives_page_side_nav_ftux","priority":2}],"workspaceId":27875370,"elevio_hash":"b0f3593313615f3951f80a7deefbddf3a4ce0c62c944278f222b74b84f98d43b"};




</script>


  </head>

  <body>
    <main id="container"></main>

    <script type="text/javascript">
    !function(){var analytics=window.analytics=window.analytics||[];if(!analytics.initialize)if(analytics.invoked)window.console&&console.error&&console.error("Segment snippet included twice.");else{analytics.invoked=!0;analytics.methods=["trackSubmit","trackClick","trackLink","trackForm","pageview","identify","reset","group","track","ready","alias","debug","page","once","off","on","addSourceMiddleware","addIntegrationMiddleware","setAnonymousId","addDestinationMiddleware"];analytics.factory=function(e){return function(){var t=Array.prototype.slice.call(arguments);t.unshift(e);analytics.push(t);return analytics}};for(var e=0;e<analytics.methods.length;e++){var key=analytics.methods[e];analytics[key]=analytics.factory(key)}analytics.load=function(key,e){var t=document.createElement("script");t.type="text/javascript";t.async=!0;t.src="https://evs.sgmt.loom.com/yhPeelcEJD/eejxbDiFfK.min.js";var n=document.getElementsByTagName("script")[0];n.parentNode.insertBefore(t,n);analytics._loadOptions=e};analytics.SNIPPET_VERSION="4.13.1";
  analytics.load("rggRFsCK29LOKVGyTLpt9xoXVhNNXaP6", { "integrations": {"Elevio":true,"Google Analytics":true,"FullStory":false} });

  

  }}();
</script>

    
  <script src="https://cdn.loom.com/assets/js/0runtime-cd3a28b1ba891ed96173.js"></script>

  <script src="https://cdn.loom.com/assets/js/react-vendor-f6d422284e4871dfe1c6.js"></script>

  <script src="https://cdn.loom.com/assets/js/3741-46c055af748a8ad652a6.js"></script>

  <script src="https://cdn.loom.com/assets/js/1596-ab287709c2ea86c8f78a.js"></script>

  <script src="https://cdn.loom.com/assets/js/2629-53c385fcfbd14beb6255.js"></script>

  <script src="https://cdn.loom.com/assets/js/5623-90493994f2d86a36d7ba.js"></script>

  <script src="https://cdn.loom.com/assets/js/6146-86335ef100b0b4ffd84f.js"></script>

  <script src="https://cdn.loom.com/assets/js/1321-1478fe6d75a710153b93.js"></script>

  <script src="https://cdn.loom.com/assets/js/2693-8430713f1e5672043785.js"></script>

  <script src="https://cdn.loom.com/assets/js/5888-9f7e0f6cde04fc685876.js"></script>

  <script src="https://cdn.loom.com/assets/js/1418-10b65bcd7c929ec9cb6d.js"></script>

  <script src="https://cdn.loom.com/assets/js/906-585ad8d9d1eabf156e12.js"></script>

  <script src="https://cdn.loom.com/assets/js/3418-5c33ab60096425ae4036.js"></script>

  <script src="https://cdn.loom.com/assets/js/1072-f47b339729f4731f40a3.js"></script>

  <script src="https://cdn.loom.com/assets/js/1738-68bc9b567d0e6204e50e.js"></script>

  <script src="https://cdn.loom.com/assets/js/4006-44d2fb941b4c48ae0f37.js"></script>

  <script src="https://cdn.loom.com/assets/js/8030-3fed0e4228bee054c15c.js"></script>

  <script src="https://cdn.loom.com/assets/js/8734-555ddda54ff3369d4579.js"></script>

  <script src="https://cdn.loom.com/assets/js/2178-42bea39cfecbb613e752.js"></script>

  <script src="https://cdn.loom.com/assets/js/5809-b630512f7bd69f91d83e.js"></script>

  <script src="https://cdn.loom.com/assets/js/3608-d10cb7d47dbddc4efb7c.js"></script>

  <script src="https://cdn.loom.com/assets/js/3316-b37b9d8ba1f8a85ee38d.js"></script>

  <script src="https://cdn.loom.com/assets/js/1771-6088957b21e4db620b7a.js"></script>

  <script src="https://cdn.loom.com/assets/js/1487-e227687f63e0039b921b.js"></script>

  <script src="https://cdn.loom.com/assets/js/destination-9877a617d0c76d7888eb.js"></script>


  </body>
</html>


https://github.com/hadep275/Notepad-project/assets/65734173/5ce97b23-8ea5-4c70-a52b-bdfde9c9e293




## Features

- **User-Friendly Interface:** The Notepad application provides a clean and intuitive user interface, resembling the familiar look of a desktop notepad.

- **Resizable Window:** Users can resize the notepad window by clicking and dragging the bottom-right corner, providing flexibility in adjusting the size according to their preferences.

- **Minimize and Close Buttons:** The window includes minimize and close buttons for easy interaction. Clicking the minimize button reduces the window to a small icon, while the close button closes the notepad.

- **Text Editing:** The core functionality of the application is text editing. Users can type and edit text in the provided textarea.

## Deployment

The Notepad web application is deployed and accessible online. You can try it out by visiting the following link:

[**Notepad Web App**](https://hadep275.github.io/Notepad-project/)

## How to Use

1. Open the deployed link in a web browser.

2. The notepad window will appear with a title bar, minimize, resize, and close buttons.

3. Resize the window by clicking and dragging the bottom-right corner.

4. Minimize the window by clicking the minimize button, and restore it by clicking the icon in the taskbar.

5. Close the notepad by clicking the close button.

6. Use the textarea to type, edit, and save your text notes.

## Styling and Customization

The application has a simple and clean style with a light background. The styling can be customized by modifying the CSS in the `<style>` section of the HTML file. Feel free to change colors, fonts, or any other styles to match your preferences.

```css
/* Example: Change background color */
body {
  background: #your-color-code;
}

/* Example: Change font family */
textarea {
  font-family: "Your Custom Font", sans-serif;
}
```

## Development and Contributions

The source code is available for further development or contributions. If you have suggestions or improvements, feel free to fork the repository, make your changes, and submit a pull request.

## License

This Notepad web application is licensed under the [MIT License](LICENSE).

---

Thank you for using the Notepad web application! If you encounter any issues or have feedback, please open an issue on the GitHub repository.
