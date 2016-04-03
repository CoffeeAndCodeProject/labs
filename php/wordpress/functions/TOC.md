# Table of Contents

- Post, Custom Post Type, Page, Attachment and Bookmarks Functions
- Category, Tag and Taxonomy Functions
- User and Author Functions
- Feed Functions
- HTTP API Functions
- Comment, Ping, and Trackback Functions
- Action, Filter, and Plugin Functions
- Theme-Related Functions
- Formatting Functions
- Miscellaneous Functions


## Posts

    # General
    get_adjacent_post
    get_boundary_post
    get_children
    get_extended
    get_next_post
    get_next_posts_link
    next_posts_link
    get_permalink
    the_permalink
    get_the_excerpt
    the_excerpt
    get_the_post_thumbnail
    get_post
    get_post_field
    get_post_ancestors
    get_post_mime_type
    get_post_status
    get_post_format
    set_post_format
    get_edit_post_link
    get_delete_post_link
    get_previous_post
    get_previous_posts_link
    previous_posts_link
    get_posts
    have_posts
    is_post (deprecated)
    is_single
    is_sticky
    get_the_ID
    the_ID
    the_post
    wp_get_recent_posts
    wp_get_single_post (deprecated)
    has_post_thumbnail
    has_excerpt
    has_post_format

    # Post insertion/removal
    wp_delete_post
    wp_insert_post
    wp_publish_post
    wp_trash_post
    wp_update_post

## Custom Post Type

    register_post_type
    is_post_type_archive
    post_type_archive_title
    add_post_type_support
    remove_post_type_support
    post_type_supports
    set_post_type
    post_type_exists
    get_post_type
    get_post_types
    get_post_type_archive_link
    get_post_type_object
    get_post_type_capabilities
    get_post_type_labels
    is_post_type_hierarchical


## Pages

    get_all_page_ids
    get_ancestors
    get_page (deprecated)
    get_page_link
    get_page_by_path
    get_page_by_title
    get_page_children
    get_page_hierarchy
    get_page_uri
    get_pages
    is_page
    page_uri_index (method of class WP_Rewrite)
    wp_link_pages
    wp_list_pages
    wp_page_menu
    wp_dropdown_pages


## Custom Fields (postmeta)

    add_post_meta
    delete_post_meta
    get_post_custom
    get_post_custom_keys
    get_post_custom_values
    get_post_meta
    update_post_meta
    register_meta


## Attachments

    get_attached_file
    image_resize (deprecated)
    image_edit_before_change (ported to WP_Image_Editor object)
    is_attachment
    is_local_attachment
    set_post_thumbnail
    update_attached_file
    wp_attachment_is_image
    wp_create_thumbnail (deprecated)
    wp_insert_attachment
    wp_delete_attachment
    wp_get_attachment_image
    wp_get_attachment_link
    wp_get_attachment_image_src
    wp_get_attachment_metadata
    wp_get_attachment_thumb_file
    wp_get_attachment_thumb_url
    wp_get_attachment_url
    wp_check_for_changed_slugs
    wp_count_posts
    wp_get_mime_types
    wp_mime_type_icon
    wp_generate_attachment_metadata
    wp_prepare_attachment_for_js
    wp_update_attachment_metadata


## Bookmarks

    get_bookmark
    get_bookmarks
    wp_list_bookmarks


## Terms

    wp_get_post_categories
    wp_set_post_categories
    wp_get_post_tags
    wp_set_post_tags
    wp_get_post_terms
    wp_set_post_terms
    wp_count_terms
    has_term
    is_object_in_term


## Others

    add_meta_box
    remove_meta_box
    get_the_ID
    the_ID
    get_the_author
    the_author
    get_the_author_posts
    get_the_content
    the_content
    get_the_title
    the_title
    the_title_attribute
    register_post_status
    wp_trim_excerpt
    wp_get_post_revision
    wp_get_post_revisions
    wp_is_post_revision
    paginate_links


## Category

    # Categories
    cat_is_ancestor_of
    get_all_category_ids
    get_ancestors
    get_cat_ID
    get_cat_name
    get_categories
    get_category
    get_category_by_path
    get_category_by_slug
    get_the_category_by_ID
    get_the_category_list
    get_category_link
    get_category_parents
    get_the_category
    single_cat_title
    in_category
    is_category
    the_category
    wp_category_checklist
    wp_dropdown_categories
    wp_list_categories

    # Category Creation
    wp_create_category
    wp_delete_category
    wp_insert_category


## Tags

    get_tag
    get_tag_link
    get_tags
    get_the_tag_list
    get_the_tags
    has_tag
    is_tag
    the_tags
    single_tag_title
    tag_description
    wp_generate_tag_cloud
    wp_tag_cloud


## Taxonomy

    get_edit_term_link
    get_taxonomy
    get_taxonomies
    get_term
    get_the_term_list
    get_term_by
    the_terms
    get_the_terms
    get_term_children
    get_term_link
    get_terms
    is_taxonomy (deprecated)
    is_taxonomy_hierarchical
    is_term (deprecated)
    taxonomy_exists
    term_exists
    register_taxonomy
    register_taxonomy_for_object_type
    wp_get_object_terms
    wp_remove_object_terms
    wp_set_object_terms
    wp_insert_term
    wp_update_term
    wp_delete_term
    wp_terms_checklist


## Admins, Roles and Capabilities

    add_cap
    add_role
    author_can
    current_user_can
    current_user_can_for_blog
    get_role
    get_super_admins
    is_super_admin
    map_meta_cap
    remove_cap
    remove_role
    user_can

## Users and Authors

    auth_redirect
    count_users
    count_user_posts
    count_many_users_posts
    email_exists
    get_currentuserinfo
    get_current_user_id
    get_profile (deprecated)
    get_user_by
    get_userdata
    get_usernumposts (deprecated)
    get_users
    set_current_user (deprecated)
    user_pass_ok (deprecated)
    wp_authenticate
    username_exists
    validate_username
    wp_dropdown_users
    wp_get_current_user
    wp_set_current_user
    wp_set_password
    get_author_posts_url
    get_the_modified_author
    is_multi_author

    ## User meta

    add_user_meta
    delete_user_meta
    get_user_meta
    update_user_meta
    get_the_author_meta

    ## User insertion/removal

    wp_create_user
    wp_delete_user
    wp_insert_user
    wp_update_user


## Login / Logout

    is_user_logged_in
    wp_login_form
    wp_signon
    wp_logout
    wp_loginout


## Feed Functions

    bloginfo_rss
    comment_author_rss
    comment_link
    comment_text_rss
    do_feed
    do_feed_atom
    do_feed_rdf
    do_feed_rss
    do_feed_rss2
    fetch_feed
    fetch_rss (deprecated)
    get_author_feed_link
    get_bloginfo_rss
    get_category_feed_link
    get_comment_link
    get_comment_author_rss
    get_post_comments_feed_link
    get_rss (deprecated)
    get_search_comments_feed_link
    get_search_feed_link
    get_the_category_rss
    get_the_title_rss
    permalink_single_rss (deprecated)
    post_comments_feed_link
    rss_enclosure
    the_title_rss
    the_category_rss
    the_content_rss (deprecated)
    the_excerpt_rss
    wp_rss (deprecated)


## HTTP API Functions

    wp_remote_get
    wp_remote_retrieve_body
    wp_get_http_headers
    wp_remote_fopen


## Comment, Ping, and Trackback Functions

    add_ping
    add_comment_meta
    check_comment
    comment_text
    comment_form
    comments_number
    discover_pingback_server_uri
    delete_comment_meta
    do_all_pings
    do_enclose
    do_trackbacks
    generic_ping
    get_approved_comments
    get_avatar
    get_comment
    get_comment_text
    get_comment_meta
    get_comments
    wp_list_comments
    get_enclosed
    get_lastcommentmodified
    get_pung
    get_to_ping
    have_comments
    get_comment_author
    is_trackback
    pingback
    privacy_ping_filter
    sanitize_comment_cookies
    trackback
    trackback_url
    trackback_url_list
    update_comment_meta
    weblog_ping
    wp_allow_comment
    wp_count_comments
    wp_delete_comment
    wp_filter_comment
    wp_get_comment_status
    wp_get_current_commenter
    wp_insert_comment
    wp_new_comment
    wp_set_comment_status
    wp_throttle_comment_flood
    wp_update_comment
    wp_update_comment_count
    wp_update_comment_count_now


## Comments

    # Comments Loop
    comment_class
    comment_ID
    comment_author
    comment_date
    comment_time
    get_comment_date
    get_comment_time

    # Comments Pagination
    paginate_comments_links
    previous_comments_link
    next_comments_link
    get_comment_pages_count


---

## Action, Filter, and Plugin Functions

### Filters (Reference)

    has_filter
    add_filter
    apply_filters
    apply_filters_ref_array
    current_filter
    merge_filters
    remove_filter
    remove_all_filters

### Actions (Reference)

    has_action
    add_action
    do_action
    do_action_ref_array
    did_action
    remove_action
    remove_all_actions

### Plugins (Reference)

    plugin_basename
    plugins_url
    get_plugin_data
    get_admin_page_title
    plugin_dir_path
    register_activation_hook
    register_deactivation_hook
    menu_page_url
    is_plugin_active
    is_plugin_active_for_network
    is_plugin_inactive
    is_plugin_page
    add_contextual_help (deprecated)
    get_plugins

### Widgets (Reference)

    is_active_widget
    register_widget
    the_widget
    unregister_widget
    wp_add_dashboard_widget
    wp_convert_widget_settings
    wp_get_sidebars_widgets
    wp_get_widget_defaults
    wp_register_sidebar_widget
    wp_register_widget_control
    wp_set_sidebars_widgets
    wp_unregister_sidebar_widget
    wp_unregister_widget_control
    wp_widget_description


### Settings (Reference)

    register_setting
    unregister_setting
    settings_fields
    do_settings_fields
    do_settings_sections
    add_settings_field
    add_settings_section
    add_settings_error
    get_settings_errors
    settings_errors

### Shortcodes (Reference)

    add_shortcode
    do_shortcode
    do_shortcode_tag
    get_shortcode_regex
    remove_shortcode
    remove_all_shortcodes
    shortcode_atts
    shortcode_parse_atts
    strip_shortcodes


## Theme-Related Functions

### Include functions

    comments_template
    get_footer
    get_header
    get_sidebar
    get_search_form


### Other functions

    add_custom_background (deprecated)
    add_custom_image_header (deprecated)
    add_image_size
    add_theme_support
    body_class
    current_theme_supports
    dynamic_sidebar
    get_404_template
    get_archive_template
    get_attachment_template
    get_author_template
    get_body_class
    get_category_template
    get_comments_popup_template
    get_current_theme
    get_date_template
    get_header_image
    get_header_textcolor
    get_home_template
    get_locale_stylesheet_uri
    get_page_template
    get_paged_template
    get_post_class
    get_query_template
    get_search_template
    get_single_template
    get_stylesheet
    get_stylesheet_directory
    get_stylesheet_directory_uri
    get_stylesheet_uri
    get_tag_template
    get_taxonomy_template
    get_template
    get_template_directory
    get_template_directory_uri
    get_template_part
    get_theme (deprecated)
    wp_get_themes
    get_theme_data (deprecated)
    get_theme_support
    get_theme_mod
    get_theme_mods
    get_theme_root
    get_theme_roots
    get_theme_root_uri
    get_themes (deprecated)
    header_image
    header_textcolor
    in_the_loop
    is_child_theme
    is_active_sidebar
    is_admin_bar_showing
    is_dynamic_sidebar
    language_attributes
    load_template
    locale_stylesheet
    locate_template
    post_class
    preview_theme
    preview_theme_ob_filter
    preview_theme_ob_filter_callback
    register_nav_menu
    register_nav_menus
    get_registered_nav_menus
    register_sidebar
    register_sidebars
    register_theme_directory
    remove_theme_mod
    remove_theme_mods
    remove_theme_support
    require_if_theme_supports
    search_theme_directories
    set_theme_mod
    switch_theme
    validate_current_theme
    unregister_nav_menu
    unregister_sidebar
    wp_add_inline_style
    wp_clean_themes_cache
    wp_get_archives
    wp_get_nav_menu_items
    wp_get_theme
    wp_nav_menu
    wp_oembed_remove_provider
    wp_page_menu
    wp_title


### Formatting Functions

    absint
    add_magic_quotes
    addslashes_gpc
    antispambot
    attribute_escape (deprecated)
    backslashit
    balanceTags
    clean_pre
    clean_url
    convert_chars
    convert_smilies
    ent2ncr
    esc_attr
    esc_html
    esc_js
    esc_textarea
    esc_sql
    esc_url
    esc_url_raw
    force_balance_tags
    format_to_edit
    format_to_post
    funky_javascript_fix (deprecated)
    htmlentities2
    is_email
    js_escape (deprecated)
    make_clickable
    popuplinks
    remove_accents
    sanitize_email
    sanitize_file_name
    sanitize_html_class
    sanitize_key
    sanitize_mime_type
    sanitize_option
    sanitize_sql_orderby
    sanitize_text_field
    sanitize_title
    sanitize_title_for_query
    sanitize_title_with_dashes
    sanitize_user
    seems_utf8
    stripslashes_deep
    trailingslashit
    untrailingslashit
    urlencode_deep
    url_shorten
    utf8_uri_encode
    wpautop
    wptexturize
    wp_filter_kses
    wp_filter_post_kses
    wp_filter_nohtml_kses
    wp_iso_descrambler
    wp_kses
    wp_kses_array_lc
    wp_kses_attr
    wp_kses_bad_protocol
    wp_kses_bad_protocol_once
    wp_kses_bad_protocol_once2
    wp_kses_check_attr_val
    wp_kses_decode_entities
    wp_kses_hair
    wp_kses_hook
    wp_kses_html_error
    wp_kses_js_entities
    wp_kses_no_null
    wp_kses_normalize_entities
    wp_kses_normalize_entities2
    wp_kses_split
    wp_kses_split2
    wp_kses_stripslashes
    wp_kses_version
    wp_make_link_relative
    wp_normalize_path
    wp_rel_nofollow
    wp_richedit_pre
    wp_specialchars
    wp_trim_words
    zeroise


## Miscellaneous Functions

### Time/Date Functions

    current_time
    date_i18n
    get_calendar
    get_date_from_gmt
    get_lastpostdate
    get_lastpostmodified
    get_day_link
    get_gmt_from_date
    get_month_link
    the_date
    get_the_date
    the_time
    get_the_time
    the_modified_time
    get_the_modified_time
    get_weekstartend
    get_year_link
    human_time_diff
    is_new_day
    iso8601_timezone_to_offset
    iso8601_to_datetime
    mysql2date

### Serialization

    is_serialized
    is_serialized_string
    maybe_serialize
    maybe_unserialize

### Options

    add_option
    add_site_option
    delete_option
    delete_site_option
    form_option
    get_alloptions (deprecated)
    get_site_option
    get_site_url
    get_admin_url
    get_user_option
    get_option
    update_option
    update_site_option
    update_user_option
    wp_load_alloptions

### Transients

    set_transient()
    get_transient()
    delete_transient()
    set_site_transient()
    get_site_transient()
    delete_site_transient()

### Admin Menu Functions

    add_menu_page
    remove_menu_page
    add_submenu_page
    remove_submenu_page
    add_object_page
    add_utility_page
    add_comments_page
    add_dashboard_page
    add_links_page
    add_management_page
    add_media_page
    add_options_page
    add_pages_page
    add_plugins_page
    add_posts_page
    add_theme_page
    add_users_page

### Toolbar Functions

    add_node
    remove_node
    add_group
    get_node
    get_nodes

### Form Helpers

    checked
    disabled
    selected
    submit_button
    get_submit_button


### Nonces and Referers (Security)

    check_admin_referer
    check_ajax_referer
    wp_create_nonce
    wp_explain_nonce (deprecated)
    wp_get_original_referer
    wp_get_referer
    wp_nonce_ays
    wp_nonce_field
    wp_nonce_url
    wp_original_referer_field
    wp_referer_field
    wp_send_json
    wp_send_json_error
    wp_send_json_success
    wp_verify_nonce

### XMLRPC

    xmlrpc_getpostcategory
    xmlrpc_getposttitle
    xmlrpc_removepostdata
    user_pass_ok (deprecated)

### Localization

    __
    _x
    _n
    _nx
    _e
    _ex
    _ngettext (deprecated)
    esc_attr__
    esc_attr_e
    get_locale
    load_default_textdomain
    load_plugin_textdomain
    load_textdomain
    load_theme_textdomain
    is_rtl

### Cron (Scheduling)

    spawn_cron
    wp_clear_scheduled_hook
    wp_cron
    wp_get_schedule
    wp_get_schedules
    wp_next_scheduled
    wp_reschedule_event
    wp_schedule_event
    wp_schedule_single_event
    wp_unschedule_event



### Conditional Tags Index

    comments_open
    has_nav_menu
    has_tag
    in_category
    is_404
    is_admin
    is_archive
    is_attachment
    is_author
    is_category
    is_comments_popup
    is_date
    is_day
    is_feed
    is_front_page
    is_home
    is_month
    is_page
    is_page_template
    is_paged
    is_preview
    is_search
    is_single
    is_singular
    is_sticky
    is_tag
    is_tax
    is_time
    is_trackback
    is_year
    pings_open

### Script and Style Registration

    wp_dequeue_script
    wp_dequeue_style
    wp_deregister_script
    wp_deregister_style
    wp_enqueue_script
    wp_enqueue_style
    wp_localize_script
    wp_register_script
    wp_register_style
    wp_script_is
    wp_style_is

### sql

    get_tax_sql
    get_meta_sql
    get_posts_by_author_sql

### Miscellaneous

    add_editor_style
    add_query_arg
    add_rewrite_rule
    admin_url
    bool_from_yn
    cache_javascript_headers
    capital_P_dangit
    clean_blog_cache
    content_url
    do_robots
    flush_rewrite_rules
    get_bloginfo
    get_num_queries
    get_post_stati
    get_post_statuses
    get_query_var
    home_url
    includes_url
    is_blog_installed
    is_main_site
    is_main_query
    is_multisite
    is_ssl
    is_wp_error
    log_app
    make_url_footnote (deprecated)
    network_admin_url
    network_home_url
    network_site_url
    nocache_headers
    plugin_dir_url
    query_posts
    remove_query_arg
    rewind_posts
    setup_postdata
    site_url
    status_header
    unzip_file
    validate_file
    validate_file_to_edit
    wp
    wp_cache_set
    wp_cache_get
    wp_cache_reset (deprecated)
    wp_check_filetype
    wp_clearcookie (deprecated)
    wp_die
    wp_editor
    wp_footer
    wp_get_cookie_login (deprecated)
    wp_get_image_editor
    wp_get_installed_translations
    wp_hash
    wp_handle_sideload
    wp_head
    wp_install_defaults
    wp_is_mobile
    wp_mail
    wp_mkdir_p
    wp_new_user_notification
    wp_password_change_notification
    wp_notify_moderator
    wp_notify_postauthor
    wp_parse_args
    wp_redirect
    wp_reset_postdata
    wp_reset_query
    wp_salt
    wp_set_auth_cookie
    wp_safe_redirect
    wp_upload_bits
    wp_upload_dir
    wp_list_pluck
    wp_text_diff
    post_submit_meta_box