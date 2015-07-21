


<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>kubernetes/README.md at master · GoogleCloudPlatform/kubernetes</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="GoogleCloudPlatform/kubernetes" name="twitter:title" /><meta content="kubernetes - Container Cluster Manager from Google" name="twitter:description" /><meta content="https://avatars0.githubusercontent.com/u/2810941?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars0.githubusercontent.com/u/2810941?v=3&amp;s=400" property="og:image" /><meta content="GoogleCloudPlatform/kubernetes" property="og:title" /><meta content="https://github.com/GoogleCloudPlatform/kubernetes" property="og:url" /><meta content="kubernetes - Container Cluster Manager from Google" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTE3NzgxNjU6NTJiZWNlYjhiNzAzMWEwM2ZlN2FhOTYyYjRjYjM3NDc6YzA3ZjRlNTBhMGE2MmRiYWQzZGI4YWE2NTFmZTI5ZDk3ZjcyM2Q3MGFjOGQ1MTBjOTZiMWJlZjczNWMzZjc0OQ==--efd0d3cb904d0d1d6a2fc6234388281a3f9f2a8c">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

        <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="499D5C3D:31E6:125CBCF:55ADE3A5" name="octolytics-dimension-request_id" /><meta content="11778165" name="octolytics-actor-id" /><meta content="jaslone20" name="octolytics-actor-login" /><meta content="6b64819eff2c442a924b0fe8d125c9995782ffcd738b0e8c01c10c3745e45ecd" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" data-pjax-transient="true" name="analytics-event" />
    <meta class="js-ga-set" name="dimension1" content="Logged In">
    <meta name="is-dotcom" content="true">
      <meta name="hostname" content="github.com">
    <meta name="user-login" content="jaslone20">

      <link rel="icon" sizes="any" mask href="https://assets-cdn.github.com/pinned-octocat.svg">
      <meta name="theme-color" content="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="tibdrsCnnu/kOFSD+79E+YgXXiwJb5x8YoVvisZBD1F+5Y/qmXCW89X/9pVVqRbukp11nyZPNEPpF45VNj2QTA==" name="csrf-token" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github/index-50695c5163ac470fa2c366bc981c3513f8feb7d6a55f8cb1c56501dc46585f0e.css" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2/index-db5a50afa754826c2474d5b59ebdf2469e8d8692a94a97705bab3e1b29c1cabc.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="366e6801cfe7e982515f3b66ce173385">

      
  <meta name="description" content="kubernetes - Container Cluster Manager from Google">
  <meta name="go-import" content="github.com/GoogleCloudPlatform/kubernetes git https://github.com/GoogleCloudPlatform/kubernetes.git">

  <meta content="2810941" name="octolytics-dimension-user_id" /><meta content="GoogleCloudPlatform" name="octolytics-dimension-user_login" /><meta content="20580498" name="octolytics-dimension-repository_id" /><meta content="GoogleCloudPlatform/kubernetes" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="20580498" name="octolytics-dimension-repository_network_root_id" /><meta content="GoogleCloudPlatform/kubernetes" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/GoogleCloudPlatform/kubernetes/commits/master.atom" rel="alternate" title="Recent Commits to kubernetes:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production macintosh vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      



        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/GoogleCloudPlatform/kubernetes/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/GoogleCloudPlatform/kubernetes/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
      </div>

      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
      <span class="js-socket-channel js-updatable-content"
        data-channel="notification-changed:jaslone20"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
          <span class="mail-status all-read"></span>
          <span class="octicon octicon-inbox"></span>
</a>  </span>

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus left"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="GoogleCloudPlatform/kubernetes">This repository</span>
  </div>
    <a class="dropdown-item" href="/GoogleCloudPlatform/kubernetes/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-s js-menu-target" href="/jaslone20"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@jaslone20" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/11778165?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu dropdown-menu-sw">
        <div class="dropdown-header header-nav-current-user css-truncate">
          Signed in as <strong class="css-truncate-target">jaslone20</strong>
        </div>
        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/jaslone20" data-ga-click="Header, go to profile, text:your profile">
          Your profile
        </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
        <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
          Explore
        </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>
        <div class="dropdown-divider"></div>

        <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
          Settings
        </a>

        <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="lEStQY7v17sA0tFayIlb/Yde/wjHsvAngik2qlLeIDa3garTTRg/Tugz+8C7YxSUV87xsG4hfrK1rBZJNy6aXA==" /></div>
          <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
            Sign out
          </button>
</form>      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>

        

        


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">

        
<ul class="pagehead-actions">

  <li>
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="MA/vsgvFz3donvH/4N01F3OUqezPVNOzHuu1/jk/WwO9O4wLPdIr9+0ti70rKPlvPOsaF6yUPvGCa6dpfcLF/g==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="20580498" />

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/GoogleCloudPlatform/kubernetes/subscription"
          class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Watch
          </span>
        </a>
        <a class="social-count js-social-count" href="/GoogleCloudPlatform/kubernetes/watchers">
          936
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                  <span class="select-menu-item-heading">Watching</span>
                  <span class="description">Be notified of all conversations.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Unwatch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_ignore" name="do" type="radio" value="ignore" />
                  <span class="select-menu-item-heading">Ignoring</span>
                  <span class="description">Never be notified.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-mute"></span>
                    Stop ignoring
                  </span>
                </div>
              </div>

            </div>

          </div>
        </div>
      </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <form accept-charset="UTF-8" action="/GoogleCloudPlatform/kubernetes/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="bD1VmQrBtP27mgsYGnUYjNjk1UZ5ZRwuxD5/6CfycGpLkBd0wDW8dKQkCIR1dX7m7HEtRSHSHYPI4v7/rbEJvw==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar GoogleCloudPlatform/kubernetes"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/GoogleCloudPlatform/kubernetes/stargazers">
          9,017
        </a>
</form>
    <form accept-charset="UTF-8" action="/GoogleCloudPlatform/kubernetes/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="wSGmigV+AbWWqqiUKmX8QJRUgP3YMc3GRi9SoP3sDjIKZH8+G+4zEF+OQWujjAzMnRp9HQ7hSfz7Ssaecqz+tw==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star GoogleCloudPlatform/kubernetes"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/GoogleCloudPlatform/kubernetes/stargazers">
          9,017
        </a>
</form>  </div>

  </li>

        <li>
          <a href="#fork-destination-box" class="btn btn-sm btn-with-count"
              title="Fork your own copy of GoogleCloudPlatform/kubernetes to your account"
              aria-label="Fork your own copy of GoogleCloudPlatform/kubernetes to your account"
              rel="facebox"
              data-ga-click="Repository, show fork modal, action:blob#show; text:Fork">
            <span class="octicon octicon-repo-forked"></span>
            Fork
          </a>
          <a href="/GoogleCloudPlatform/kubernetes/network" class="social-count">2,059</a>

          <div id="fork-destination-box" style="display: none;">
            <h2 class="facebox-header">Where should we fork this repository?</h2>
            <include-fragment src=""
                class="js-fork-select-fragment fork-select-fragment"
                data-url="/GoogleCloudPlatform/kubernetes/fork?fragment=1">
              <img alt="Loading" height="64" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-128.gif" width="64" />
            </include-fragment>
          </div>
        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/GoogleCloudPlatform" class="url fn" itemprop="url" rel="author"><span itemprop="title">GoogleCloudPlatform</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/GoogleCloudPlatform/kubernetes" data-pjax="#js-repo-pjax-container">kubernetes</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/GoogleCloudPlatform/kubernetes/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/GoogleCloudPlatform/kubernetes" aria-label="Code" aria-selected="true" class="js-selected-navigation-item selected sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /GoogleCloudPlatform/kubernetes">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/GoogleCloudPlatform/kubernetes/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /GoogleCloudPlatform/kubernetes/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/GoogleCloudPlatform/kubernetes/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /GoogleCloudPlatform/kubernetes/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/GoogleCloudPlatform/kubernetes/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /GoogleCloudPlatform/kubernetes/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/GoogleCloudPlatform/kubernetes/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /GoogleCloudPlatform/kubernetes/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/GoogleCloudPlatform/kubernetes/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /GoogleCloudPlatform/kubernetes/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
</a>    </li>
  </ul>


</nav>

              <div class="only-with-full-nav">
                  
<div class="js-clone-url clone-url open"
  data-protocol-type="http">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/GoogleCloudPlatform/kubernetes.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="ssh">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:GoogleCloudPlatform/kubernetes.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="js-clone-url clone-url "
  data-protocol-type="subversion">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/GoogleCloudPlatform/kubernetes" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<div class="clone-options">You can clone with
  <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="tAS4YBiWQMbySlhKwZil7+UqaYR+wTuJbnBv0vkN5wMcJmLXsdbMiHODaJhxzNMeYOx7e0xXmRxl/YF3AEAi7w==" /></div><button class="btn-link js-clone-selector" data-protocol="http" type="submit">HTTPS</button></form>, <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="9vC9UBNaU/YOxB5CbJwyf9sfoX2YHhQFgIcbGeVUoH23C4dqZ978nOzAAPbaRXGOk3bfrNXGAvEX5vvWft9gjQ==" /></div><button class="btn-link js-clone-selector" data-protocol="ssh" type="submit">SSH</button></form>, or <form accept-charset="UTF-8" action="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone" class="inline-form js-clone-selector-form is-enabled" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="qGHUVJg8c/BjBSia2efO+0/Z16wejTfjJQUv3BNGZUuhsJA8RrgAMKnKHKpoRfixCDe/wrUPmN2TeznH2elxlg==" /></div><button class="btn-link js-clone-selector" data-protocol="subversion" type="submit">Subversion</button></form>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</div>

  <a href="github-mac://openRepo/https://github.com/GoogleCloudPlatform/kubernetes" class="btn btn-sm sidebar-button" title="Save GoogleCloudPlatform/kubernetes to your computer and use it in GitHub Desktop." aria-label="Save GoogleCloudPlatform/kubernetes to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>



                <a href="/GoogleCloudPlatform/kubernetes/archive/master.zip"
                   class="btn btn-sm sidebar-button"
                   aria-label="Download the contents of GoogleCloudPlatform/kubernetes as a zip file"
                   title="Download the contents of GoogleCloudPlatform/kubernetes as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>

          

<a href="/GoogleCloudPlatform/kubernetes/blob/fbc85e9838f25547be94fbffeeb92a756d908ca0/examples/guestbook/README.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:b73f0873a685abe66c998eb6b897e6c0 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/conformance-test-v1/examples/guestbook/README.md"
               data-name="conformance-test-v1"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="conformance-test-v1">
                conformance-test-v1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/external-services-proposal/examples/guestbook/README.md"
               data-name="external-services-proposal"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="external-services-proposal">
                external-services-proposal
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/gh-pages/examples/guestbook/README.md"
               data-name="gh-pages"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="gh-pages">
                gh-pages
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/gsoc/examples/guestbook/README.md"
               data-name="gsoc"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="gsoc">
                gsoc
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/GoogleCloudPlatform/kubernetes/blob/master/examples/guestbook/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/quinton-hoole-demote-docker-e2e/examples/guestbook/README.md"
               data-name="quinton-hoole-demote-docker-e2e"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="quinton-hoole-demote-docker-e2e">
                quinton-hoole-demote-docker-e2e
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/quinton-hoole-fix-ubernetes-shortlink/examples/guestbook/README.md"
               data-name="quinton-hoole-fix-ubernetes-shortlink"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="quinton-hoole-fix-ubernetes-shortlink">
                quinton-hoole-fix-ubernetes-shortlink
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/quinton-hoole-multiline-e2e-regex/examples/guestbook/README.md"
               data-name="quinton-hoole-multiline-e2e-regex"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="quinton-hoole-multiline-e2e-regex">
                quinton-hoole-multiline-e2e-regex
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/quinton-hoole-patch-1/examples/guestbook/README.md"
               data-name="quinton-hoole-patch-1"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="quinton-hoole-patch-1">
                quinton-hoole-patch-1
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.4/examples/guestbook/README.md"
               data-name="release-0.4"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.4">
                release-0.4
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.5/examples/guestbook/README.md"
               data-name="release-0.5"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.5">
                release-0.5
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.6/examples/guestbook/README.md"
               data-name="release-0.6"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.6">
                release-0.6
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.7/examples/guestbook/README.md"
               data-name="release-0.7"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.7">
                release-0.7
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.8/examples/guestbook/README.md"
               data-name="release-0.8"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.8">
                release-0.8
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.9/examples/guestbook/README.md"
               data-name="release-0.9"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.9">
                release-0.9
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.10/examples/guestbook/README.md"
               data-name="release-0.10"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.10">
                release-0.10
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.12/examples/guestbook/README.md"
               data-name="release-0.12"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.12">
                release-0.12
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.13/examples/guestbook/README.md"
               data-name="release-0.13"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.13">
                release-0.13
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.14/examples/guestbook/README.md"
               data-name="release-0.14"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.14">
                release-0.14
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.15/examples/guestbook/README.md"
               data-name="release-0.15"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.15">
                release-0.15
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.16/examples/guestbook/README.md"
               data-name="release-0.16"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.16">
                release-0.16
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.17/examples/guestbook/README.md"
               data-name="release-0.17"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.17">
                release-0.17
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.18/examples/guestbook/README.md"
               data-name="release-0.18"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.18">
                release-0.18
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.19/examples/guestbook/README.md"
               data-name="release-0.19"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.19">
                release-0.19
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.20/examples/guestbook/README.md"
               data-name="release-0.20"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.20">
                release-0.20
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-0.21/examples/guestbook/README.md"
               data-name="release-0.21"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-0.21">
                release-0.21
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/release-1.0/examples/guestbook/README.md"
               data-name="release-1.0"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="release-1.0">
                release-1.0
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-9354-logSpam/examples/guestbook/README.md"
               data-name="revert-9354-logSpam"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-9354-logSpam">
                revert-9354-logSpam
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-9390-bump_ectd_client/examples/guestbook/README.md"
               data-name="revert-9390-bump_ectd_client"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-9390-bump_ectd_client">
                revert-9390-bump_ectd_client
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-9426-release-0.18/examples/guestbook/README.md"
               data-name="revert-9426-release-0.18"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-9426-release-0.18">
                revert-9426-release-0.18
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-9569-unclear_error/examples/guestbook/README.md"
               data-name="revert-9569-unclear_error"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-9569-unclear_error">
                revert-9569-unclear_error
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-9685-secure/examples/guestbook/README.md"
               data-name="revert-9685-secure"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-9685-secure">
                revert-9685-secure
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-9688-validate_pod_spec/examples/guestbook/README.md"
               data-name="revert-9688-validate_pod_spec"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-9688-validate_pod_spec">
                revert-9688-validate_pod_spec
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-9715-big_archive/examples/guestbook/README.md"
               data-name="revert-9715-big_archive"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-9715-big_archive">
                revert-9715-big_archive
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-9728-aws_id_as_name/examples/guestbook/README.md"
               data-name="revert-9728-aws_id_as_name"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-9728-aws_id_as_name">
                revert-9728-aws_id_as_name
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-9736-bug_fix2/examples/guestbook/README.md"
               data-name="revert-9736-bug_fix2"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-9736-bug_fix2">
                revert-9736-bug_fix2
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-9862-bump_ectd_client/examples/guestbook/README.md"
               data-name="revert-9862-bump_ectd_client"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-9862-bump_ectd_client">
                revert-9862-bump_ectd_client
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-10083-revert-9688-validate_pod_spec/examples/guestbook/README.md"
               data-name="revert-10083-revert-9688-validate_pod_spec"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-10083-revert-9688-validate_pod_spec">
                revert-10083-revert-9688-validate_pod_spec
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-10211-cleanup/examples/guestbook/README.md"
               data-name="revert-10211-cleanup"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-10211-cleanup">
                revert-10211-cleanup
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-10260-clean/examples/guestbook/README.md"
               data-name="revert-10260-clean"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-10260-clean">
                revert-10260-clean
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/GoogleCloudPlatform/kubernetes/blob/revert-10690-version-api-descriptions/examples/guestbook/README.md"
               data-name="revert-10690-version-api-descriptions"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="revert-10690-version-api-descriptions">
                revert-10690-version-api-descriptions
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v1.0.1/examples/guestbook/README.md"
                 data-name="v1.0.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v1.0.1">v1.0.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v1.0.0/examples/guestbook/README.md"
                 data-name="v1.0.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v1.0.0">v1.0.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.21.4/examples/guestbook/README.md"
                 data-name="v0.21.4"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.21.4">v0.21.4</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.21.3/examples/guestbook/README.md"
                 data-name="v0.21.3"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.21.3">v0.21.3</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.21.2/examples/guestbook/README.md"
                 data-name="v0.21.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.21.2">v0.21.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.21.1/examples/guestbook/README.md"
                 data-name="v0.21.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.21.1">v0.21.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.21.0/examples/guestbook/README.md"
                 data-name="v0.21.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.21.0">v0.21.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.20.2/examples/guestbook/README.md"
                 data-name="v0.20.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.20.2">v0.20.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.20.1/examples/guestbook/README.md"
                 data-name="v0.20.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.20.1">v0.20.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.20.0/examples/guestbook/README.md"
                 data-name="v0.20.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.20.0">v0.20.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.19.3/examples/guestbook/README.md"
                 data-name="v0.19.3"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.19.3">v0.19.3</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.19.2/examples/guestbook/README.md"
                 data-name="v0.19.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.19.2">v0.19.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.19.1/examples/guestbook/README.md"
                 data-name="v0.19.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.19.1">v0.19.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.19.0/examples/guestbook/README.md"
                 data-name="v0.19.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.19.0">v0.19.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.18.2/examples/guestbook/README.md"
                 data-name="v0.18.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.18.2">v0.18.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.18.1/examples/guestbook/README.md"
                 data-name="v0.18.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.18.1">v0.18.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.18.0/examples/guestbook/README.md"
                 data-name="v0.18.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.18.0">v0.18.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.17.1/examples/guestbook/README.md"
                 data-name="v0.17.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.17.1">v0.17.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.17.0/examples/guestbook/README.md"
                 data-name="v0.17.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.17.0">v0.17.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.16.2/examples/guestbook/README.md"
                 data-name="v0.16.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.16.2">v0.16.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.16.1/examples/guestbook/README.md"
                 data-name="v0.16.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.16.1">v0.16.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.16.0/examples/guestbook/README.md"
                 data-name="v0.16.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.16.0">v0.16.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.15.0/examples/guestbook/README.md"
                 data-name="v0.15.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.15.0">v0.15.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.14.2/examples/guestbook/README.md"
                 data-name="v0.14.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.14.2">v0.14.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.14.1/examples/guestbook/README.md"
                 data-name="v0.14.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.14.1">v0.14.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.14.0/examples/guestbook/README.md"
                 data-name="v0.14.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.14.0">v0.14.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.13.2/examples/guestbook/README.md"
                 data-name="v0.13.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.13.2">v0.13.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.13.1-dev/examples/guestbook/README.md"
                 data-name="v0.13.1-dev"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.13.1-dev">v0.13.1-dev</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.13.1/examples/guestbook/README.md"
                 data-name="v0.13.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.13.1">v0.13.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.13.0/examples/guestbook/README.md"
                 data-name="v0.13.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.13.0">v0.13.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.12.2/examples/guestbook/README.md"
                 data-name="v0.12.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.12.2">v0.12.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.12.1/examples/guestbook/README.md"
                 data-name="v0.12.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.12.1">v0.12.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.12.0/examples/guestbook/README.md"
                 data-name="v0.12.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.12.0">v0.12.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.11.0/examples/guestbook/README.md"
                 data-name="v0.11.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.11.0">v0.11.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.10.1/examples/guestbook/README.md"
                 data-name="v0.10.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.10.1">v0.10.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.10.0/examples/guestbook/README.md"
                 data-name="v0.10.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.10.0">v0.10.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.9.3/examples/guestbook/README.md"
                 data-name="v0.9.3"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.9.3">v0.9.3</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.9.2/examples/guestbook/README.md"
                 data-name="v0.9.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.9.2">v0.9.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.9.1/examples/guestbook/README.md"
                 data-name="v0.9.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.9.1">v0.9.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.9.0/examples/guestbook/README.md"
                 data-name="v0.9.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.9.0">v0.9.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.8.4/examples/guestbook/README.md"
                 data-name="v0.8.4"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.8.4">v0.8.4</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.8.2/examples/guestbook/README.md"
                 data-name="v0.8.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.8.2">v0.8.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.8.1/examples/guestbook/README.md"
                 data-name="v0.8.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.8.1">v0.8.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.8.0/examples/guestbook/README.md"
                 data-name="v0.8.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.8.0">v0.8.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.7.4/examples/guestbook/README.md"
                 data-name="v0.7.4"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.7.4">v0.7.4</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.7.3/examples/guestbook/README.md"
                 data-name="v0.7.3"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.7.3">v0.7.3</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.7.2/examples/guestbook/README.md"
                 data-name="v0.7.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.7.2">v0.7.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.7.1/examples/guestbook/README.md"
                 data-name="v0.7.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.7.1">v0.7.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.7.0/examples/guestbook/README.md"
                 data-name="v0.7.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.7.0">v0.7.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.6.2/examples/guestbook/README.md"
                 data-name="v0.6.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.6.2">v0.6.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.6.1/examples/guestbook/README.md"
                 data-name="v0.6.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.6.1">v0.6.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.6.0/examples/guestbook/README.md"
                 data-name="v0.6.0"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.6.0">v0.6.0</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.5.6/examples/guestbook/README.md"
                 data-name="v0.5.6"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.5.6">v0.5.6</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.5.5/examples/guestbook/README.md"
                 data-name="v0.5.5"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.5.5">v0.5.5</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.5.4/examples/guestbook/README.md"
                 data-name="v0.5.4"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.5.4">v0.5.4</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.5.3/examples/guestbook/README.md"
                 data-name="v0.5.3"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.5.3">v0.5.3</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.5.2/examples/guestbook/README.md"
                 data-name="v0.5.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.5.2">v0.5.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.5.1/examples/guestbook/README.md"
                 data-name="v0.5.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.5.1">v0.5.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.5/examples/guestbook/README.md"
                 data-name="v0.5"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.5">v0.5</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.4.4/examples/guestbook/README.md"
                 data-name="v0.4.4"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.4.4">v0.4.4</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.4.3/examples/guestbook/README.md"
                 data-name="v0.4.3"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.4.3">v0.4.3</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.4.2/examples/guestbook/README.md"
                 data-name="v0.4.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.4.2">v0.4.2</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.4.1/examples/guestbook/README.md"
                 data-name="v0.4.1"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.4.1">v0.4.1</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.4/examples/guestbook/README.md"
                 data-name="v0.4"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.4">v0.4</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.3/examples/guestbook/README.md"
                 data-name="v0.3"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.3">v0.3</a>
            </div>
            <div class="select-menu-item js-navigation-item ">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <a href="/GoogleCloudPlatform/kubernetes/tree/v0.2/examples/guestbook/README.md"
                 data-name="v0.2"
                 data-skip-pjax="true"
                 rel="nofollow"
                 class="js-navigation-open select-menu-item-text css-truncate-target"
                 title="v0.2">v0.2</a>
            </div>
        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="btn-group right">
    <a href="/GoogleCloudPlatform/kubernetes/find/master"
          class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/GoogleCloudPlatform/kubernetes" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">kubernetes</span></a></span></span><span class="separator">/</span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/GoogleCloudPlatform/kubernetes/tree/master/examples" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">examples</span></a></span><span class="separator">/</span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/GoogleCloudPlatform/kubernetes/tree/master/examples/guestbook" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">guestbook</span></a></span><span class="separator">/</span><strong class="final-path">README.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="@satnam6502" class="avatar" height="24" src="https://avatars2.githubusercontent.com/u/6164339?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/satnam6502" rel="contributor">satnam6502</a></span>
        <time datetime="2015-07-18T22:03:55Z" is="relative-time">Jul 18, 2015</time>
        <div class="commit-title">
            <a href="/GoogleCloudPlatform/kubernetes/commit/1a0d309a3cb22fa81fc2e47c1fd3c9fba042382e" class="message" data-pjax="true" title="Convert shell to console outpout for Guestbook example documentation">Convert shell to console outpout for Guestbook example documentation</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>38</strong>
           contributors
        </a>
      </p>
          <a class="avatar-link tooltipped tooltipped-s" aria-label="thockin" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=thockin"><img alt="@thockin" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/5595220?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="jayunit100" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=jayunit100"><img alt="@jayunit100" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/826111?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="brendandburns" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=brendandburns"><img alt="@brendandburns" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/5751682?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="jbeda" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=jbeda"><img alt="@jbeda" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/37310?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="jlowdermilk" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=jlowdermilk"><img alt="@jlowdermilk" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/2101035?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="lavalamp" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=lavalamp"><img alt="@lavalamp" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/647318?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="piosz" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=piosz"><img alt="@piosz" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/10819974?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="ddysher" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=ddysher"><img alt="@ddysher" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/2191361?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="caesarxuchao" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=caesarxuchao"><img alt="@caesarxuchao" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/2823529?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="RichieEscarez" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=RichieEscarez"><img alt="@RichieEscarez" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/11762685?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="bgrant0607" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=bgrant0607"><img alt="@bgrant0607" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/7725777?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="timstclair" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=timstclair"><img alt="@timstclair" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/3272040?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="mikedanese" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=mikedanese"><img alt="@mikedanese" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/1787169?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="you-n-g" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=you-n-g"><img alt="@you-n-g" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/465606?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="krousey" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=krousey"><img alt="@krousey" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/157083?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="skonzem" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=skonzem"><img alt="@skonzem" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/11252754?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="soundTricker" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=soundTricker"><img alt="@soundTricker" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/421752?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="mbforbes" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=mbforbes"><img alt="@mbforbes" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/1170062?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="nikhiljindal" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=nikhiljindal"><img alt="@nikhiljindal" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/10199099?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="rjnagal" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=rjnagal"><img alt="@rjnagal" class="avatar" height="20" src="https://avatars3.githubusercontent.com/u/5420489?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="pierredup" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=pierredup"><img alt="@pierredup" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/144858?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="roberthbailey" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=roberthbailey"><img alt="@roberthbailey" class="avatar" height="20" src="https://avatars1.githubusercontent.com/u/7751204?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="ihmccreery" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=ihmccreery"><img alt="@ihmccreery" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/368416?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="gosharplite" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=gosharplite"><img alt="@gosharplite" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/5064483?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="goltermann" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=goltermann"><img alt="@goltermann" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/9358478?v=3&amp;s=40" width="20" /> </a>
    <a class="avatar-link tooltipped tooltipped-s" aria-label="rsokolowski" href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md?author=rsokolowski"><img alt="@rsokolowski" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/10743336?v=3&amp;s=40" width="20" /> </a>

    <a href="#blob_contributors_box" rel="facebox" class="others-text">and others</a>

    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="@thockin" height="24" src="https://avatars1.githubusercontent.com/u/5595220?v=3&amp;s=48" width="24" />
            <a href="/thockin">thockin</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@jayunit100" height="24" src="https://avatars0.githubusercontent.com/u/826111?v=3&amp;s=48" width="24" />
            <a href="/jayunit100">jayunit100</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@brendandburns" height="24" src="https://avatars1.githubusercontent.com/u/5751682?v=3&amp;s=48" width="24" />
            <a href="/brendandburns">brendandburns</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@jbeda" height="24" src="https://avatars3.githubusercontent.com/u/37310?v=3&amp;s=48" width="24" />
            <a href="/jbeda">jbeda</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@jlowdermilk" height="24" src="https://avatars2.githubusercontent.com/u/2101035?v=3&amp;s=48" width="24" />
            <a href="/jlowdermilk">jlowdermilk</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@lavalamp" height="24" src="https://avatars3.githubusercontent.com/u/647318?v=3&amp;s=48" width="24" />
            <a href="/lavalamp">lavalamp</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@piosz" height="24" src="https://avatars2.githubusercontent.com/u/10819974?v=3&amp;s=48" width="24" />
            <a href="/piosz">piosz</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@ddysher" height="24" src="https://avatars2.githubusercontent.com/u/2191361?v=3&amp;s=48" width="24" />
            <a href="/ddysher">ddysher</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@caesarxuchao" height="24" src="https://avatars1.githubusercontent.com/u/2823529?v=3&amp;s=48" width="24" />
            <a href="/caesarxuchao">caesarxuchao</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@RichieEscarez" height="24" src="https://avatars0.githubusercontent.com/u/11762685?v=3&amp;s=48" width="24" />
            <a href="/RichieEscarez">RichieEscarez</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@bgrant0607" height="24" src="https://avatars1.githubusercontent.com/u/7725777?v=3&amp;s=48" width="24" />
            <a href="/bgrant0607">bgrant0607</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@timstclair" height="24" src="https://avatars3.githubusercontent.com/u/3272040?v=3&amp;s=48" width="24" />
            <a href="/timstclair">timstclair</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@mikedanese" height="24" src="https://avatars2.githubusercontent.com/u/1787169?v=3&amp;s=48" width="24" />
            <a href="/mikedanese">mikedanese</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@you-n-g" height="24" src="https://avatars3.githubusercontent.com/u/465606?v=3&amp;s=48" width="24" />
            <a href="/you-n-g">you-n-g</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@krousey" height="24" src="https://avatars1.githubusercontent.com/u/157083?v=3&amp;s=48" width="24" />
            <a href="/krousey">krousey</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@skonzem" height="24" src="https://avatars2.githubusercontent.com/u/11252754?v=3&amp;s=48" width="24" />
            <a href="/skonzem">skonzem</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@soundTricker" height="24" src="https://avatars1.githubusercontent.com/u/421752?v=3&amp;s=48" width="24" />
            <a href="/soundTricker">soundTricker</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@mbforbes" height="24" src="https://avatars2.githubusercontent.com/u/1170062?v=3&amp;s=48" width="24" />
            <a href="/mbforbes">mbforbes</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@nikhiljindal" height="24" src="https://avatars0.githubusercontent.com/u/10199099?v=3&amp;s=48" width="24" />
            <a href="/nikhiljindal">nikhiljindal</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@rjnagal" height="24" src="https://avatars1.githubusercontent.com/u/5420489?v=3&amp;s=48" width="24" />
            <a href="/rjnagal">rjnagal</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@pierredup" height="24" src="https://avatars3.githubusercontent.com/u/144858?v=3&amp;s=48" width="24" />
            <a href="/pierredup">pierredup</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@roberthbailey" height="24" src="https://avatars3.githubusercontent.com/u/7751204?v=3&amp;s=48" width="24" />
            <a href="/roberthbailey">roberthbailey</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@ihmccreery" height="24" src="https://avatars0.githubusercontent.com/u/368416?v=3&amp;s=48" width="24" />
            <a href="/ihmccreery">ihmccreery</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@gosharplite" height="24" src="https://avatars2.githubusercontent.com/u/5064483?v=3&amp;s=48" width="24" />
            <a href="/gosharplite">gosharplite</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@goltermann" height="24" src="https://avatars2.githubusercontent.com/u/9358478?v=3&amp;s=48" width="24" />
            <a href="/goltermann">goltermann</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@rsokolowski" height="24" src="https://avatars2.githubusercontent.com/u/10743336?v=3&amp;s=48" width="24" />
            <a href="/rsokolowski">rsokolowski</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@derekwaynecarr" height="24" src="https://avatars1.githubusercontent.com/u/6233452?v=3&amp;s=48" width="24" />
            <a href="/derekwaynecarr">derekwaynecarr</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@satnam6502" height="24" src="https://avatars2.githubusercontent.com/u/6164339?v=3&amp;s=48" width="24" />
            <a href="/satnam6502">satnam6502</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@cjcullen" height="24" src="https://avatars3.githubusercontent.com/u/7154008?v=3&amp;s=48" width="24" />
            <a href="/cjcullen">cjcullen</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@smarterclayton" height="24" src="https://avatars0.githubusercontent.com/u/1163175?v=3&amp;s=48" width="24" />
            <a href="/smarterclayton">smarterclayton</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@scuxiayiqian" height="24" src="https://avatars1.githubusercontent.com/u/5508376?v=3&amp;s=48" width="24" />
            <a href="/scuxiayiqian">scuxiayiqian</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@gtaylor" height="24" src="https://avatars2.githubusercontent.com/u/75556?v=3&amp;s=48" width="24" />
            <a href="/gtaylor">gtaylor</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@shichao-an" height="24" src="https://avatars2.githubusercontent.com/u/5781687?v=3&amp;s=48" width="24" />
            <a href="/shichao-an">shichao-an</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@amygdala" height="24" src="https://avatars1.githubusercontent.com/u/115093?v=3&amp;s=48" width="24" />
            <a href="/amygdala">amygdala</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@komljen" height="24" src="https://avatars0.githubusercontent.com/u/2872288?v=3&amp;s=48" width="24" />
            <a href="/komljen">komljen</a>
          </li>
          <li class="facebox-user-list-item">
            <img alt="@juzna" height="24" src="https://avatars2.githubusercontent.com/u/227416?v=3&amp;s=48" width="24" />
            <a href="/juzna">juzna</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
    <div class="file-actions">

      <div class="btn-group">
        <a href="/GoogleCloudPlatform/kubernetes/raw/master/examples/guestbook/README.md" class="btn btn-sm " id="raw-url">Raw</a>
          <a href="/GoogleCloudPlatform/kubernetes/blame/master/examples/guestbook/README.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
        <a href="/GoogleCloudPlatform/kubernetes/commits/master/examples/guestbook/README.md" class="btn btn-sm " rel="nofollow">History</a>
      </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="github-mac://openRepo/https://github.com/GoogleCloudPlatform/kubernetes?branch=master&amp;filepath=examples%2Fguestbook%2FREADME.md"
           aria-label="Open this file in GitHub for Mac"
           data-ga-click="Repository, open with desktop, type:mac">
            <span class="octicon octicon-device-desktop"></span>
        </a>

            <form accept-charset="UTF-8" action="/GoogleCloudPlatform/kubernetes/edit/master/examples/guestbook/README.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="DvEgioqdH4+Ab+Pb8TI5FMBpFKRFKkmThOVskUqgjMAieWQ8i32crkfht8wBopAvbao2EAfyeIMrwdOcvssxcA==" /></div>
              <button class="octicon-btn tooltipped tooltipped-n" type="submit" aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
                <span class="octicon octicon-pencil"></span>
              </button>
</form>
          <form accept-charset="UTF-8" action="/GoogleCloudPlatform/kubernetes/delete/master/examples/guestbook/README.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="cPRjO/5fFaX2INCgKXo86HEDAd+USMgNANJ/9KE882YyWu0e3yOD+Y6E4SeM9faftt3UwWIDTEk2U/GGLLiEtw==" /></div>
            <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-n" type="submit" aria-label="Fork this project and delete this file" data-disable-with>
              <span class="octicon octicon-trashcan"></span>
            </button>
</form>    </div>

    <div class="file-info">
        582 lines (433 sloc)
        <span class="file-info-divider"></span>
      25.603 kB
    </div>
  </div>
  
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage">



<p><a href="https://camo.githubusercontent.com/de7fd8d7080ff6dd8b87ee1f40e816d8263896d8/687474703a2f2f6b756265726e657465732e696f2f696d672f7761726e696e672e706e67" target="_blank"><img src="https://camo.githubusercontent.com/de7fd8d7080ff6dd8b87ee1f40e816d8263896d8/687474703a2f2f6b756265726e657465732e696f2f696d672f7761726e696e672e706e67" alt="WARNING" width="25" height="25" data-canonical-src="http://kubernetes.io/img/warning.png" style="max-width:100%;"></a>
<a href="https://camo.githubusercontent.com/de7fd8d7080ff6dd8b87ee1f40e816d8263896d8/687474703a2f2f6b756265726e657465732e696f2f696d672f7761726e696e672e706e67" target="_blank"><img src="https://camo.githubusercontent.com/de7fd8d7080ff6dd8b87ee1f40e816d8263896d8/687474703a2f2f6b756265726e657465732e696f2f696d672f7761726e696e672e706e67" alt="WARNING" width="25" height="25" data-canonical-src="http://kubernetes.io/img/warning.png" style="max-width:100%;"></a>
<a href="https://camo.githubusercontent.com/de7fd8d7080ff6dd8b87ee1f40e816d8263896d8/687474703a2f2f6b756265726e657465732e696f2f696d672f7761726e696e672e706e67" target="_blank"><img src="https://camo.githubusercontent.com/de7fd8d7080ff6dd8b87ee1f40e816d8263896d8/687474703a2f2f6b756265726e657465732e696f2f696d672f7761726e696e672e706e67" alt="WARNING" width="25" height="25" data-canonical-src="http://kubernetes.io/img/warning.png" style="max-width:100%;"></a>
<a href="https://camo.githubusercontent.com/de7fd8d7080ff6dd8b87ee1f40e816d8263896d8/687474703a2f2f6b756265726e657465732e696f2f696d672f7761726e696e672e706e67" target="_blank"><img src="https://camo.githubusercontent.com/de7fd8d7080ff6dd8b87ee1f40e816d8263896d8/687474703a2f2f6b756265726e657465732e696f2f696d672f7761726e696e672e706e67" alt="WARNING" width="25" height="25" data-canonical-src="http://kubernetes.io/img/warning.png" style="max-width:100%;"></a>
<a href="https://camo.githubusercontent.com/de7fd8d7080ff6dd8b87ee1f40e816d8263896d8/687474703a2f2f6b756265726e657465732e696f2f696d672f7761726e696e672e706e67" target="_blank"><img src="https://camo.githubusercontent.com/de7fd8d7080ff6dd8b87ee1f40e816d8263896d8/687474703a2f2f6b756265726e657465732e696f2f696d672f7761726e696e672e706e67" alt="WARNING" width="25" height="25" data-canonical-src="http://kubernetes.io/img/warning.png" style="max-width:100%;"></a></p>

<h2><a id="user-content-please-note-this-document-applies-to-the-head-of-the-source-tree" class="anchor" href="#please-note-this-document-applies-to-the-head-of-the-source-tree" aria-hidden="true"><span class="octicon octicon-link"></span></a>PLEASE NOTE: This document applies to the HEAD of the source tree</h2>

<p>If you are using a released version of Kubernetes, you should
refer to the docs that go with that version.</p>

<p><strong>
The latest 1.0.x release of this document can be found
<a href="http://releases.k8s.io/release-1.0/examples/guestbook/README.md">here</a>.</strong></p><strong>

<p>Documentation for other releases can be found at
<a href="http://releases.k8s.io">releases.k8s.io</a>.</p>

</strong><h2><a id="" class="anchor" href="#" aria-hidden="true"><span class="octicon octicon-link"></span></a><strong></strong></h2>





<h2><a id="user-content-guestbook-example" class="anchor" href="#guestbook-example" aria-hidden="true"><span class="octicon octicon-link"></span></a>Guestbook Example</h2>

<p>This example shows how to build a simple, multi-tier web application using Kubernetes and <a href="https://www.docker.com/">Docker</a>.</p>

<p><strong>Table of Contents</strong></p>

<ul>
<li><a href="#step-zero-prerequisites">Step Zero: Prerequisites</a></li>
<li><a href="#step-one-start-up-the-redis-master">Step One: Start up the redis master</a>

<ul>
<li><a href="#optional-interlude">Optional Interlude</a></li>
</ul></li>
<li><a href="#step-two-fire-up-the-redis-master-service">Step Two: Fire up the redis master service</a>

<ul>
<li><a href="#finding-a-service">Finding a service</a></li>
</ul></li>
<li><a href="#step-three-fire-up-the-replicated-slave-pods">Step Three: Fire up the replicated slave pods</a></li>
<li><a href="#step-four-create-the-redis-slave-service">Step Four: Create the redis slave service</a></li>
<li><a href="#step-five-create-the-frontend-replicated-pods">Step Five: Create the frontend replicated pods</a></li>
<li><a href="#step-six-set-up-the-guestbook-frontend-service">Step Six: Set up the guestbook frontend service.</a>

<ul>
<li><a href="#using-type-loadbalancer-for-the-frontend-service-cloud-provider-specific">Using 'type: LoadBalancer' for the frontend service (cloud-provider-specific)</a></li>
<li><a href="#create-the-frontend-service">Create the Frontend Service</a></li>
<li><a href="#accessing-the-guestbook-site-externally">Accessing the guestbook site externally</a>

<ul>
<li><a href="#gce-external-load-balancer-specifics">Google Compute Engine External Load Balancer Specifics</a></li>
</ul></li>
</ul></li>
<li><a href="#step-seven-cleanup">Step Seven: Cleanup</a></li>
<li><a href="#troubleshooting">Troubleshooting</a></li>
</ul>

<p>The example consists of:</p>

<ul>
<li>A web frontend</li>
<li>A <a href="http://redis.io/">redis</a> master (for storage), and a replicated set of redis 'slaves'.</li>
</ul>

<p>The web front end interacts with the redis master via javascript redis API calls.</p>

<p><strong>Note</strong>:  If you are running this example on a <a href="https://cloud.google.com/container-engine/">Google Container Engine</a> installation, see <a href="https://cloud.google.com/container-engine/docs/tutorials/guestbook">this Container Engine guestbook walkthrough</a> instead. The basic concepts are the same, but the walkthrough is tailored to a Container Engine setup.</p>

<h3><a id="user-content-step-zero-prerequisites" class="anchor" href="#step-zero-prerequisites" aria-hidden="true"><span class="octicon octicon-link"></span></a>Step Zero: Prerequisites</h3>

<p>This example requires a running Kubernetes cluster.  See the <a href="/GoogleCloudPlatform/kubernetes/blob/master/docs/getting-started-guides">Getting Started guides</a> for how to get started. As noted above, if you have a Google Container Engine cluster set up, go <a href="https://cloud.google.com/container-engine/docs/tutorials/guestbook">here</a> instead.</p>

<h3><a id="user-content-step-one-start-up-the-redis-master" class="anchor" href="#step-one-start-up-the-redis-master" aria-hidden="true"><span class="octicon octicon-link"></span></a>Step One: Start up the redis master</h3>

<p><strong>Note</strong>: The redis master in this example is <em>not</em> highly available.  Making it highly available would be an interesting, but intricate exercise— redis doesn't actually support multi-master deployments at this point in time, so high availability would be a somewhat tricky thing to implement, and might involve periodic serialization to disk, and so on.</p>

<p>To start the redis master, use the file <code>examples/guestbook/redis-master-controller.yaml</code>, which describes a single <a href="/GoogleCloudPlatform/kubernetes/blob/master/docs/user-guide/pods.md">pod</a> running a redis key-value server in a container.</p>

<p>Although we have a single instance of our redis master, we are using a <a href="/GoogleCloudPlatform/kubernetes/blob/master/docs/user-guide/replication-controller.md">replication controller</a> to enforce that exactly one pod keeps running. E.g., if the node were to go down, the replication controller will ensure that the redis master gets restarted on a healthy node. (In our simplified example, this could result in data loss.)</p>

<p>Here is <code>redis-master-controller.yaml</code>:</p>

<div class="highlight highlight-yaml"><pre><span class="pl-s"><span class="pl-ent">apiVersion:</span> <span class="pl-s">v1</span></span>
<span class="pl-s"><span class="pl-ent">kind:</span> <span class="pl-s">ReplicationController</span></span>
<span class="pl-s"><span class="pl-ent">metadata:</span></span>
  <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-master</span></span>
  <span class="pl-s"><span class="pl-ent">labels:</span></span>
    <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-master</span></span>
<span class="pl-s"><span class="pl-ent">spec:</span></span>
  <span class="pl-c1"><span class="pl-ent">replicas:</span> 1</span>
  <span class="pl-s"><span class="pl-ent">selector:</span></span>
    <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-master</span></span>
  <span class="pl-s"><span class="pl-ent">template:</span></span>
    <span class="pl-s"><span class="pl-ent">metadata:</span></span>
      <span class="pl-s"><span class="pl-ent">labels:</span></span>
        <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-master</span></span>
    <span class="pl-s"><span class="pl-ent">spec:</span></span>
      <span class="pl-s"><span class="pl-ent">containers:</span></span>
      <span class="pl-s">- <span class="pl-ent">name:</span> <span class="pl-s">master</span></span>
        <span class="pl-s"><span class="pl-ent">image:</span> <span class="pl-s">redis</span></span>
        <span class="pl-s"><span class="pl-ent">ports:</span></span>
        <span class="pl-c1">- <span class="pl-ent">containerPort:</span> 6379</span></pre></div>

<p>Change to the <code>&lt;kubernetes&gt;/examples/guestbook</code> directory if you're not already there. Create the redis master pod in your Kubernetes cluster by running:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl create -f examples/guestbook/redis-master-controller.yaml</span>
<span class="pl-mo">replicationcontrollers/redis-master</span></pre></div>

<p>The <code>replicationcontrollers/redis-master</code> line is the expected response to this operation.
You can see the replication controllers for your cluster by running:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl get rc</span>
<span class="pl-mo">CONTROLLER                             CONTAINER(S)            IMAGE(S)                                 SELECTOR                     REPLICAS</span>
<span class="pl-mo">redis-master                           master                  redis                                    name=redis-master            1</span></pre></div>

<p>Then, you can list the pods in the cluster, to verify that the master is running:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl get pods</span></pre></div>

<p>You'll see all pods in the cluster, including the redis master pod, and the status of each pod.
The name of the redis master will look similar to that in the following list:</p>

<div class="highlight highlight-console"><pre><span class="pl-mo">NAME                                           READY     STATUS    RESTARTS   AGE</span>
<span class="pl-mo">...</span>
<span class="pl-mo">redis-master-dz33o                             1/1       Running   0          2h</span></pre></div>

<p>(Note that an initial <code>docker pull</code> to grab a container image may take a few minutes, depending on network conditions. A pod will be reported as <code>Pending</code> while its image is being downloaded.)</p>

<h4><a id="user-content-optional-interlude" class="anchor" href="#optional-interlude" aria-hidden="true"><span class="octicon octicon-link"></span></a>Optional Interlude</h4>

<p>You can get information about a pod, including the machine that it is running on, via <code>kubectl describe pods/&lt;pod_name&gt;</code>.  E.g., for the redis master, you should see something like the following (your pod name will be different):</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl describe pods/redis-master-dz33o</span>
<span class="pl-mo">...</span>
<span class="pl-mo">Name:       redis-master-dz33o</span>
<span class="pl-mo">Image(s):     redis</span>
<span class="pl-mo">Node:       kubernetes-minion-krxw/10.240.67.201</span>
<span class="pl-mo">Labels:       name=redis-master</span>
<span class="pl-mo">Status:       Running</span>
<span class="pl-mo">Replication Controllers:  redis-master (1/1 replicas created)</span>
<span class="pl-mo">Containers:</span>
<span class="pl-mo">  master:</span>
<span class="pl-mo">    Image:    redis</span>
<span class="pl-mo">    State:    Running</span>
<span class="pl-mo">      Started:    Fri, 12 Jun 2015 12:53:46 -0700</span>
<span class="pl-mo">    Ready:    True</span>
<span class="pl-mo">    Restart Count:  0</span>
<span class="pl-mo">Conditions:</span>
<span class="pl-mo">  Type    Status</span>
<span class="pl-mo">  Ready   True</span>
<span class="pl-mo">No events.</span></pre></div>

<p>The 'Node' is the name of the machine, e.g. <code>kubernetes-minion-krxw</code> in the example above.</p>

<p>If you want to view the container logs for a given pod, you can run:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl logs <span class="pl-k">&lt;</span>pod_name<span class="pl-k">&gt;</span></span></pre></div>

<p>These logs will usually give you enough information to troubleshoot.</p>

<p>However, if you should want to SSH to the listed host machine, you can inspect various logs there directly as well.  For example, with Google Compute Engine, using <code>gcloud</code>, you can SSH like this:</p>

<div class="highlight highlight-console"><pre><span class="pl-e">me@workstation</span>$ <span class="pl-s1">gcloud compute ssh kubernetes-minion-krxw</span></pre></div>

<p>Then, you can look at the docker containers on the remote machine.  You should see something like this (the specifics of the IDs will be different):</p>

<div class="highlight highlight-console"><pre><span class="pl-e">me@kubernetes-minion-krxw:~</span>$ <span class="pl-s1">sudo docker ps</span>
<span class="pl-mo">CONTAINER ID        IMAGE                                  COMMAND                CREATED              STATUS              PORTS                    NAMES</span>
<span class="pl-mo">...</span>
<span class="pl-mo">0ffef9649265        redis:latest                           "redis-server /etc/r"   About a minute ago   Up About a minute                            k8s_redis-master.767aef46_redis-master-controller-gb50a.default.api_4530d7b3-ae5d-11e4-bf77-42010af0d719_579ee964</span></pre></div>

<p>If you want to see the logs for a given container, you can run:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">docker logs <span class="pl-k">&lt;</span>container_id<span class="pl-k">&gt;</span></span></pre></div>

<h3><a id="user-content-step-two-fire-up-the-redis-master-service" class="anchor" href="#step-two-fire-up-the-redis-master-service" aria-hidden="true"><span class="octicon octicon-link"></span></a>Step Two: Fire up the redis master service</h3>

<p>A Kubernetes <a href="/GoogleCloudPlatform/kubernetes/blob/master/docs/user-guide/services.md">service</a> is a named load balancer that proxies traffic to one or more containers. This is done using the <a href="/GoogleCloudPlatform/kubernetes/blob/master/docs/user-guide/labels.md">labels</a> metadata that we defined in the <code>redis-master</code> pod above.  As mentioned, we have only one redis master, but we nevertheless want to create a service for it.  Why?  Because it gives us a deterministic way to route to the single master using an elastic IP.</p>

<p>Services find the pods to load balance based on the pods' labels.
The pod that you created in <a href="#step-one-start-up-the-redis-master">Step One</a> has the label <code>name=redis-master</code>.
The selector field of the service description determines which pods will receive the traffic sent to the service, and the <code>port</code> and <code>targetPort</code> information defines what port the service proxy will run at.</p>

<p>The file <code>examples/guestbook/redis-master-service.yaml</code> defines the redis master service:</p>

<div class="highlight highlight-yaml"><pre><span class="pl-s"><span class="pl-ent">apiVersion:</span> <span class="pl-s">v1</span></span>
<span class="pl-s"><span class="pl-ent">kind:</span> <span class="pl-s">Service</span></span>
<span class="pl-s"><span class="pl-ent">metadata:</span></span>
  <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-master</span></span>
  <span class="pl-s"><span class="pl-ent">labels:</span></span>
    <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-master</span></span>
<span class="pl-s"><span class="pl-ent">spec:</span></span>
  <span class="pl-s"><span class="pl-ent">ports:</span></span>
    <span class="pl-c"># the port that this service should serve on</span>
  <span class="pl-c1">- <span class="pl-ent">port:</span> 6379</span>
    <span class="pl-c1"><span class="pl-ent">targetPort:</span> 6379</span>
  <span class="pl-s"><span class="pl-ent">selector:</span></span>
    <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-master</span></span></pre></div>

<p>Create the service by running:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl create -f examples/guestbook/redis-master-service.yaml</span>
<span class="pl-mo">services/redis-master</span></pre></div>

<p>Then check the list of services, which should include the redis-master:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl get services</span>
<span class="pl-mo">NAME                    LABELS                                    SELECTOR                     IP                  PORT</span>
<span class="pl-mo">redis-master            name=redis-master                         name=redis-master            10.0.246.242        6379</span></pre></div>

<p>This will cause all pods to see the redis master apparently running on :6379.  A service can map an incoming port to any <code>targetPort</code> in the backend pod.  Once created, the service proxy on each node is configured to set up a proxy on the specified port (in this case port 6379).</p>

<p><code>targetPort</code> will default to <code>port</code> if it is omitted in the configuration. For simplicity's sake, we omit it in the following configurations.</p>

<p>The traffic flow from slaves to masters can be described in two steps, like so:</p>

<ul>
<li>A <em>redis slave</em> will connect to "port" on the <em>redis master service</em></li>
<li>Traffic will be forwarded from the service "port" (on the service node) to the  <em>targetPort</em> on the pod that the service listens to.</li>
</ul>

<h4><a id="user-content-finding-a-service" class="anchor" href="#finding-a-service" aria-hidden="true"><span class="octicon octicon-link"></span></a>Finding a service</h4>

<p>Kubernetes supports two primary modes of finding a service— environment variables and DNS.</p>

<p>The services in a Kubernetes cluster are discoverable inside other containers <a href="/GoogleCloudPlatform/kubernetes/blob/master/docs/user-guide/services.md#environment-variables">via environment variables</a>.</p>

<p>An alternative is to use the <a href="/GoogleCloudPlatform/kubernetes/blob/master/docs/user-guide/services.md#dns">cluster's DNS service</a>, if it has been enabled for the cluster.  This lets all pods do name resolution of services automatically, based on the service name.
We'll use the DNS service for this example.  E.g., you can see the service name, <code>redis-master</code>, accessed as a <code>host</code> value in the PHP script in <a href="#step-five-create-the-frontend-replicated-pods">Step 5</a>.</p>

<p><strong>Note</strong>: <strong>If your cluster does not have the DNS service enabled, then this example will not work out of the box.</strong> You will need to edit <code>examples/guestbook/php-redis/index.php</code> to use environment variables for service discovery instead, then rebuild the container image from the <code>Dockerfile</code> in that directory.  (However, this is unlikely to be necessary. You can check for the DNS service in the list of the clusters' services.)</p>

<h3><a id="user-content-step-three-fire-up-the-replicated-slave-pods" class="anchor" href="#step-three-fire-up-the-replicated-slave-pods" aria-hidden="true"><span class="octicon octicon-link"></span></a>Step Three: Fire up the replicated slave pods</h3>

<p>Now that the redis master is running, we can start up its 'read slaves'.</p>

<p>We'll define these as replicated pods as well, though this time— unlike for the redis master— we'll define the number of replicas to be 2.
In Kubernetes, a replication controller is responsible for managing multiple instances of a replicated pod.  The replication controller will automatically launch new pods if the number of replicas falls below the specified number.
(This particular replicated pod is a great one to test this with -- you can try killing the docker processes for your pods directly, then watch them come back online on a new node shortly thereafter.)</p>

<p>To create the replicated pod, use the file <code>examples/guestbook/redis-slave-controller.yaml</code>, which looks like this:</p>

<div class="highlight highlight-yaml"><pre><span class="pl-s"><span class="pl-ent">apiVersion:</span> <span class="pl-s">v1</span></span>
<span class="pl-s"><span class="pl-ent">kind:</span> <span class="pl-s">ReplicationController</span></span>
<span class="pl-s"><span class="pl-ent">metadata:</span></span>
  <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-slave</span></span>
  <span class="pl-s"><span class="pl-ent">labels:</span></span>
    <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-slave</span></span>
<span class="pl-s"><span class="pl-ent">spec:</span></span>
  <span class="pl-c1"><span class="pl-ent">replicas:</span> 2</span>
  <span class="pl-s"><span class="pl-ent">selector:</span></span>
    <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-slave</span></span>
  <span class="pl-s"><span class="pl-ent">template:</span></span>
    <span class="pl-s"><span class="pl-ent">metadata:</span></span>
      <span class="pl-s"><span class="pl-ent">labels:</span></span>
        <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-slave</span></span>
    <span class="pl-s"><span class="pl-ent">spec:</span></span>
      <span class="pl-s"><span class="pl-ent">containers:</span></span>
      <span class="pl-s">- <span class="pl-ent">name:</span> <span class="pl-s">worker</span></span>
        <span class="pl-s"><span class="pl-ent">image:</span> <span class="pl-s">kubernetes/redis-slave:v2</span></span>
        <span class="pl-s"><span class="pl-ent">ports:</span></span>
        <span class="pl-c1">- <span class="pl-ent">containerPort:</span> 6379</span></pre></div>

<p>and create the replication controller by running:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl create -f examples/guestbook/redis-slave-controller.yaml</span>
<span class="pl-mo">replicationcontrollers/redis-slave</span>

$ <span class="pl-s1">kubectl get rc</span>
<span class="pl-mo">CONTROLLER                             CONTAINER(S)            IMAGE(S)                                 SELECTOR                     REPLICAS</span>
<span class="pl-mo">redis-master                           master                  redis                                    name=redis-master            1</span>
<span class="pl-mo">redis-slave                            slave                   kubernetes/redis-slave:v2                name=redis-slave             2</span></pre></div>

<p>Once the replication controller is up, you can list the pods in the cluster, to verify that the master and slaves are running.  You should see a list that includes something like the following:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl get pods</span>
<span class="pl-mo">NAME                                           READY     STATUS    RESTARTS   AGE</span>
<span class="pl-mo">...</span>
<span class="pl-mo">redis-master-dz33o                             1/1       Running   0          2h</span>
<span class="pl-mo">redis-slave-35mer                              1/1       Running   0          2h</span>
<span class="pl-mo">redis-slave-iqkhy                              1/1       Running   0          2h</span></pre></div>

<p>You should see a single redis master pod and two redis slave pods.  As mentioned above, you can get more information about any pod with: <code>kubectl describe pods/&lt;pod_name&gt;</code>.</p>

<h3><a id="user-content-step-four-create-the-redis-slave-service" class="anchor" href="#step-four-create-the-redis-slave-service" aria-hidden="true"><span class="octicon octicon-link"></span></a>Step Four: Create the redis slave service</h3>

<p>Just like the master, we want to have a service to proxy connections to the redis slaves. In this case, in addition to discovery, the slave service will provide transparent load balancing to web app clients.</p>

<p>The service specification for the slaves is in <code>examples/guestbook/redis-slave-service.yaml</code>:</p>

<div class="highlight highlight-yaml"><pre><span class="pl-s"><span class="pl-ent">apiVersion:</span> <span class="pl-s">v1</span></span>
<span class="pl-s"><span class="pl-ent">kind:</span> <span class="pl-s">Service</span></span>
<span class="pl-s"><span class="pl-ent">metadata:</span></span>
  <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-slave</span></span>
  <span class="pl-s"><span class="pl-ent">labels:</span></span>
    <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-slave</span></span>
<span class="pl-s"><span class="pl-ent">spec:</span></span>
  <span class="pl-s"><span class="pl-ent">ports:</span></span>
    <span class="pl-c"># the port that this service should serve on</span>
  <span class="pl-c1">- <span class="pl-ent">port:</span> 6379</span>
  <span class="pl-s"><span class="pl-ent">selector:</span></span>
    <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">redis-slave</span></span></pre></div>

<p>This time the selector for the service is <code>name=redis-slave</code>, because that identifies the pods running redis slaves. It may also be helpful to set labels on your service itself as we've done here to make it easy to locate them with the <code>kubectl get services -l "label=value"</code> command.</p>

<p>Now that you have created the service specification, create it in your cluster by running:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl create -f examples/guestbook/redis-slave-service.yaml</span>
<span class="pl-mo">services/redis-slave</span>

$ <span class="pl-s1">kubectl get services</span>
<span class="pl-mo">NAME                    LABELS                                    SELECTOR                     IP                  PORT</span>
<span class="pl-mo">redis-master            name=redis-master                         name=redis-master            10.0.246.242        6379</span>
<span class="pl-mo">redis-slave             name=redis-slave                          name=redis-slave             10.0.72.62          6379</span></pre></div>

<h3><a id="user-content-step-five-create-the-frontend-replicated-pods" class="anchor" href="#step-five-create-the-frontend-replicated-pods" aria-hidden="true"><span class="octicon octicon-link"></span></a>Step Five: Create the frontend replicated pods</h3>

<p><a href="#step-five-create-the-frontend-replicated-pods"></a></p>

<p>A frontend pod is a simple PHP server that is configured to talk to either the slave or master services, depending on whether the client request is a read or a write. It exposes a simple AJAX interface, and serves an Angular-based UX.
Again we'll create a set of replicated frontend pods instantiated by a replication controller— this time, with three replicas.</p>

<p>The pod is described in the file <code>examples/guestbook/frontend-controller.yaml</code>:</p>

<div class="highlight highlight-yaml"><pre><span class="pl-s"><span class="pl-ent">apiVersion:</span> <span class="pl-s">v1</span></span>
<span class="pl-s"><span class="pl-ent">kind:</span> <span class="pl-s">ReplicationController</span></span>
<span class="pl-s"><span class="pl-ent">metadata:</span></span>
  <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">frontend</span></span>
  <span class="pl-s"><span class="pl-ent">labels:</span></span>
    <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">frontend</span></span>
<span class="pl-s"><span class="pl-ent">spec:</span></span>
  <span class="pl-c1"><span class="pl-ent">replicas:</span> 3</span>
  <span class="pl-s"><span class="pl-ent">selector:</span></span>
    <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">frontend</span></span>
  <span class="pl-s"><span class="pl-ent">template:</span></span>
    <span class="pl-s"><span class="pl-ent">metadata:</span></span>
      <span class="pl-s"><span class="pl-ent">labels:</span></span>
        <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">frontend</span></span>
    <span class="pl-s"><span class="pl-ent">spec:</span></span>
      <span class="pl-s"><span class="pl-ent">containers:</span></span>
      <span class="pl-s">- <span class="pl-ent">name:</span> <span class="pl-s">php-redis</span></span>
        <span class="pl-s"><span class="pl-ent">image:</span> <span class="pl-s">kubernetes/example-guestbook-php-redis:v2</span></span>
        <span class="pl-s"><span class="pl-ent">ports:</span></span>
        <span class="pl-c1">- <span class="pl-ent">containerPort:</span> 80</span></pre></div>

<p>Using this file, you can turn up your frontend with:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl create -f examples/guestbook/frontend-controller.yaml</span>
<span class="pl-mo">replicationcontrollers/frontend</span></pre></div>

<p>Then, list all your replication controllers:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl get rc</span>
<span class="pl-mo">CONTROLLER                             CONTAINER(S)            IMAGE(S)                                   SELECTOR                     REPLICAS</span>
<span class="pl-mo">frontend                               php-redis               kubernetes/example-guestbook-php-redis:v2  name=frontend                3</span>
<span class="pl-mo">redis-master                           master                  redis                                      name=redis-master            1</span>
<span class="pl-mo">redis-slave                            slave                   kubernetes/redis-slave:v2                  name=redis-slave             2</span></pre></div>

<p>Once it's up (again, it may take up to thirty seconds to create the pods) you can list the pods in the cluster, to verify that the master, slaves and frontends are all running.  You should see a list that includes something like the following:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl get pods</span>
<span class="pl-mo">NAME                                           READY     STATUS    RESTARTS   AGE</span>
<span class="pl-mo">...</span>
<span class="pl-mo">frontend-4o11g                                 1/1       Running   0          2h</span>
<span class="pl-mo">frontend-u9aq6                                 1/1       Running   0          2h</span>
<span class="pl-mo">frontend-yga1l                                 1/1       Running   0          2h</span>
<span class="pl-mo">...</span>
<span class="pl-mo">redis-master-dz33o                             1/1       Running   0          2h</span>
<span class="pl-mo">redis-slave-35mer                              1/1       Running   0          2h</span>
<span class="pl-mo">redis-slave-iqkhy                              1/1       Running   0          2h</span></pre></div>

<p>You should see a single redis master pod, two redis slaves, and three frontend pods.</p>

<p>The code for the PHP server that the frontends are running looks like this:</p>

<div class="highlight highlight-php"><pre><span class="pl-s1"><span class="pl-k">&lt;</span>?</span>
<span class="pl-s1"></span>
<span class="pl-s1"><span class="pl-c1">set_include_path</span>(<span class="pl-s"><span class="pl-pds">'</span>.:/usr/share/php:/usr/share/pear:/vendor/predis<span class="pl-pds">'</span></span>);</span>
<span class="pl-s1"></span>
<span class="pl-s1"><span class="pl-c1">error_reporting</span>(<span class="pl-c1">E_ALL</span>);</span>
<span class="pl-s1"><span class="pl-c1">ini_set</span>(<span class="pl-s"><span class="pl-pds">'</span>display_errors<span class="pl-pds">'</span></span>, <span class="pl-c1">1</span>);</span>
<span class="pl-s1"></span>
<span class="pl-s1"><span class="pl-k">require</span> <span class="pl-s"><span class="pl-pds">'</span>predis/autoload.php<span class="pl-pds">'</span></span>;</span>
<span class="pl-s1"></span>
<span class="pl-s1"><span class="pl-k">if</span> (<span class="pl-c1">isset</span>(<span class="pl-smi">$_GET</span>[<span class="pl-s"><span class="pl-pds">'</span>cmd<span class="pl-pds">'</span></span>]) <span class="pl-k">===</span> <span class="pl-c1">true</span>) {</span>
<span class="pl-s1">  <span class="pl-c1">header</span>(<span class="pl-s"><span class="pl-pds">'</span>Content-Type: application/json<span class="pl-pds">'</span></span>);</span>
<span class="pl-s1">  <span class="pl-k">if</span> (<span class="pl-smi">$_GET</span>[<span class="pl-s"><span class="pl-pds">'</span>cmd<span class="pl-pds">'</span></span>] <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">'</span>set<span class="pl-pds">'</span></span>) {</span>
<span class="pl-s1">    <span class="pl-smi">$client</span> <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-c1">Predis\</span><span class="pl-c1">Client</span>([</span>
<span class="pl-s1">      <span class="pl-s"><span class="pl-pds">'</span>scheme<span class="pl-pds">'</span></span> <span class="pl-k">=&gt;</span> <span class="pl-s"><span class="pl-pds">'</span>tcp<span class="pl-pds">'</span></span>,</span>
<span class="pl-s1">      <span class="pl-s"><span class="pl-pds">'</span>host<span class="pl-pds">'</span></span>   <span class="pl-k">=&gt;</span> <span class="pl-s"><span class="pl-pds">'</span>redis-master<span class="pl-pds">'</span></span>,</span>
<span class="pl-s1">      <span class="pl-s"><span class="pl-pds">'</span>port<span class="pl-pds">'</span></span>   <span class="pl-k">=&gt;</span> <span class="pl-c1">6379</span>,</span>
<span class="pl-s1">    ]);</span>
<span class="pl-s1"></span>
<span class="pl-s1">    <span class="pl-smi">$client</span><span class="pl-k">-&gt;</span>set(<span class="pl-smi">$_GET</span>[<span class="pl-s"><span class="pl-pds">'</span>key<span class="pl-pds">'</span></span>], <span class="pl-smi">$_GET</span>[<span class="pl-s"><span class="pl-pds">'</span>value<span class="pl-pds">'</span></span>]);</span>
<span class="pl-s1">    <span class="pl-c1">print</span>(<span class="pl-s"><span class="pl-pds">'</span>{"message": "Updated"}<span class="pl-pds">'</span></span>);</span>
<span class="pl-s1">  } <span class="pl-k">else</span> {</span>
<span class="pl-s1">    <span class="pl-smi">$client</span> <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-c1">Predis\</span><span class="pl-c1">Client</span>([</span>
<span class="pl-s1">      <span class="pl-s"><span class="pl-pds">'</span>scheme<span class="pl-pds">'</span></span> <span class="pl-k">=&gt;</span> <span class="pl-s"><span class="pl-pds">'</span>tcp<span class="pl-pds">'</span></span>,</span>
<span class="pl-s1">      <span class="pl-s"><span class="pl-pds">'</span>host<span class="pl-pds">'</span></span>   <span class="pl-k">=&gt;</span> <span class="pl-s"><span class="pl-pds">'</span>redis-slave<span class="pl-pds">'</span></span>,</span>
<span class="pl-s1">      <span class="pl-s"><span class="pl-pds">'</span>port<span class="pl-pds">'</span></span>   <span class="pl-k">=&gt;</span> <span class="pl-c1">6379</span>,</span>
<span class="pl-s1">    ]);</span>
<span class="pl-s1"></span>
<span class="pl-s1">    <span class="pl-smi">$value</span> <span class="pl-k">=</span> <span class="pl-smi">$client</span><span class="pl-k">-&gt;</span>get(<span class="pl-smi">$_GET</span>[<span class="pl-s"><span class="pl-pds">'</span>key<span class="pl-pds">'</span></span>]);</span>
<span class="pl-s1">    <span class="pl-c1">print</span>(<span class="pl-s"><span class="pl-pds">'</span>{"data": "<span class="pl-pds">'</span></span> <span class="pl-k">.</span> <span class="pl-smi">$value</span> <span class="pl-k">.</span> <span class="pl-s"><span class="pl-pds">'</span>"}<span class="pl-pds">'</span></span>);</span>
<span class="pl-s1">  }</span>
<span class="pl-s1">} <span class="pl-k">else</span> {</span>
<span class="pl-s1">  <span class="pl-c1">phpinfo</span>();</span>
<span class="pl-s1">} </span><span class="pl-pse"><span class="pl-s1">?</span>&gt;</span></pre></div>

<p>Note the use of the <code>redis-master</code> and <code>redis-slave</code> host names-- we're finding those services via the Kubernetes cluster's DNS service, as discussed above.  All the frontend replicas will write to the load-balancing redis-slaves service, which can be highly replicated as well.</p>

<h3><a id="user-content-step-six-set-up-the-guestbook-frontend-service" class="anchor" href="#step-six-set-up-the-guestbook-frontend-service" aria-hidden="true"><span class="octicon octicon-link"></span></a>Step Six: Set up the guestbook frontend service.</h3>

<p>As with the other pods, we now want to create a service to group your frontend pods.
The service is described in the file <code>frontend-service.yaml</code>:</p>

<div class="highlight highlight-yaml"><pre><span class="pl-s"><span class="pl-ent">apiVersion:</span> <span class="pl-s">v1</span></span>
<span class="pl-s"><span class="pl-ent">kind:</span> <span class="pl-s">Service</span></span>
<span class="pl-s"><span class="pl-ent">metadata:</span></span>
  <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">frontend</span></span>
  <span class="pl-s"><span class="pl-ent">labels:</span></span>
    <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">frontend</span></span>
<span class="pl-s"><span class="pl-ent">spec:</span></span>
  <span class="pl-c"># if your cluster supports it, uncomment the following to automatically create</span>
  <span class="pl-c"># an external load-balanced IP for the frontend service.</span>
  <span class="pl-c"># type: LoadBalancer</span>
  <span class="pl-s"><span class="pl-ent">ports:</span></span>
    <span class="pl-c"># the port that this service should serve on</span>
  <span class="pl-c1">- <span class="pl-ent">port:</span> 80</span>
  <span class="pl-s"><span class="pl-ent">selector:</span></span>
    <span class="pl-s"><span class="pl-ent">name:</span> <span class="pl-s">frontend</span></span></pre></div>

<h4><a id="user-content-using-type-loadbalancer-for-the-frontend-service-cloud-provider-specific" class="anchor" href="#using-type-loadbalancer-for-the-frontend-service-cloud-provider-specific" aria-hidden="true"><span class="octicon octicon-link"></span></a>Using 'type: LoadBalancer' for the frontend service (cloud-provider-specific)</h4>

<p>For supported cloud providers, such as Google Compute Engine or Google Container Engine, you can specify to use an external load balancer
in the service <code>spec</code>, to expose the service onto an external load balancer IP.
To do this, uncomment the <code>type: LoadBalancer</code> line in the <code>frontend-service.yaml</code> file before you start the service.</p>

<p><a href="#accessing-the-guestbook-site-externally">See the section below</a> on accessing the guestbook site externally for more details.</p>

<h4><a id="user-content-create-the-frontend-service" class="anchor" href="#create-the-frontend-service" aria-hidden="true"><span class="octicon octicon-link"></span></a>Create the Frontend Service</h4>

<p>Create the service like this:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl create -f examples/guestbook/frontend-service.yaml</span>
<span class="pl-mo">services/frontend</span></pre></div>

<p>Then, list all your services again:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl get services</span>
<span class="pl-mo">NAME                    LABELS                                    SELECTOR                     IP                  PORT(S)</span>
<span class="pl-mo">frontend                name=frontend                             name=frontend                10.0.93.211         80/TCP</span>
<span class="pl-mo">redis-master            name=redis-master                         name=redis-master            10.0.246.242        6379/TCP</span>
<span class="pl-mo">redis-slave             name=redis-slave                          name=redis-slave             10.0.72.62          6379/TCP</span></pre></div>

<h4><a id="user-content-accessing-the-guestbook-site-externally" class="anchor" href="#accessing-the-guestbook-site-externally" aria-hidden="true"><span class="octicon octicon-link"></span></a>Accessing the guestbook site externally</h4>

<p><a href="#accessing-the-guestbook-site-externally"></a></p>

<p>You'll want to set up your guestbook service so that it can be accessed from outside of the internal Kubernetes network. Above, we introduced one way to do that, using the <code>type: LoadBalancer</code> spec.</p>

<p>More generally, Kubernetes supports two ways of exposing a service onto an external IP address: <code>NodePort</code>s and <code>LoadBalancer</code>s , as described <a href="/GoogleCloudPlatform/kubernetes/blob/master/docs/user-guide/services.md#external-services">here</a>.</p>

<p>If the <code>LoadBalancer</code> specification is used, it can take a short period for an external IP to show up in <code>kubectl get services</code> output, but you should shortly see it listed as well, e.g. like this:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">kubectl get services</span>
<span class="pl-mo">NAME                    LABELS                                    SELECTOR                     IP                  PORT(S)</span>
<span class="pl-mo">frontend                name=frontend                             name=frontend                10.0.93.211         80/TCP</span>
<span class="pl-mo">                                                                                               130.211.135.84</span>
<span class="pl-mo">redis-master            name=redis-master                         name=redis-master            10.0.246.242        6379/TCP</span>
<span class="pl-mo">redis-slave             name=redis-slave                          name=redis-slave             10.0.72.62          6379/TCP</span></pre></div>

<p>Once you've exposed the service to an external IP, visit the IP to see your guestbook in action. E.g., <code>http://130.211.188.51:80</code> in the example above.</p>

<p>You should see a web page that looks something like this (without the messages).  Try adding some entries to it!</p>

<p><a href="https://camo.githubusercontent.com/8aa2be605fd7dd7938124447823728d27326d167/687474703a2f2f616d792d6a6f2e73746f726167652e676f6f676c65617069732e636f6d2f696d616765732f67625f6b38735f6578312e706e67" target="_blank"><img width="50%" src="https://camo.githubusercontent.com/8aa2be605fd7dd7938124447823728d27326d167/687474703a2f2f616d792d6a6f2e73746f726167652e676f6f676c65617069732e636f6d2f696d616765732f67625f6b38735f6578312e706e67" data-canonical-src="http://amy-jo.storage.googleapis.com/images/gb_k8s_ex1.png" style="max-width:100%;"></a></p>

<p>If you are more advanced in the ops arena, you can also manually get the service IP from looking at the output of <code>kubectl get pods,services</code>, and modify your firewall using standard tools and services (firewalld, iptables, selinux) which you are already familiar with.</p>

<h5><a id="user-content-google-compute-engine-external-load-balancer-specifics" class="anchor" href="#google-compute-engine-external-load-balancer-specifics" aria-hidden="true"><span class="octicon octicon-link"></span></a>Google Compute Engine External Load Balancer Specifics</h5>

<p>In Google Compute Engine, <code>kubectl</code> automatically creates forwarding rule for services with <code>LoadBalancer</code>.</p>

<p>You can list the forwarding rules like this.  The forwarding rule also indicates the external IP.</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">gcloud compute forwarding-rules list</span>
<span class="pl-mo">NAME                  REGION      IP_ADDRESS     IP_PROTOCOL TARGET</span>
<span class="pl-mo">frontend              us-central1 130.211.188.51 TCP         us-central1/targetPools/frontend</span></pre></div>

<p>In Google Compute Engine, you also may need to open the firewall for port 80 using the <a href="https://console.developer.google.com">console</a> or the <code>gcloud</code> tool. The following command will allow traffic from any source to instances tagged <code>kubernetes-minion</code> (replace with your tags as appropriate):</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1">gcloud compute firewall-rules create --allow=tcp:80 --target-tags=kubernetes-minion kubernetes-minion-80</span></pre></div>

<p>For Google Compute Engine details about limiting traffic to specific sources, see the <a href="https://cloud.google.com/compute/docs/networking#firewalls">Google Compute Engine firewall documentation</a>.</p>

<h3><a id="user-content-step-seven-cleanup" class="anchor" href="#step-seven-cleanup" aria-hidden="true"><span class="octicon octicon-link"></span></a>Step Seven: Cleanup</h3>

<p>If you are in a live kubernetes cluster, you can just kill the pods by stopping the replication controllers and deleting the services.  Using labels to select the resources to stop or delete is an easy way to do this in one command.</p>

<div class="highlight highlight-console"><pre><span class="pl-mo">kubectl stop rc -l "name in (redis-master, redis-slave, frontend)"</span>
<span class="pl-mo">kubectl delete service -l "name in (redis-master, redis-slave, frontend)"</span></pre></div>

<p>To completely tear down a Kubernetes cluster, if you ran this from source, you can use:</p>

<div class="highlight highlight-console"><pre>$ <span class="pl-s1"><span class="pl-k">&lt;</span>kubernetes<span class="pl-k">&gt;</span>/cluster/kube-down.sh</span></pre></div>

<h3><a id="user-content-troubleshooting" class="anchor" href="#troubleshooting" aria-hidden="true"><span class="octicon octicon-link"></span></a>Troubleshooting</h3>

<p>If you are having trouble bringing up your guestbook app, double check that your external IP is properly defined for your frontend service, and that the firewall for your cluster nodes is open to port 80.</p>

<p>Then, see the <a href="/GoogleCloudPlatform/kubernetes/blob/master/docs/troubleshooting.md">troubleshooting documentation</a> for a further list of common issues and how you can diagnose them.</p>



<p><a href="/GoogleCloudPlatform/kubernetes/blob/master/examples/guestbook"><img src="https://camo.githubusercontent.com/61a8ccc9b43782f60a87de2fc6a389d4fe594821/68747470733a2f2f6b756265726e657465732d736974652e61707073706f742e636f6d2f55412d33363033373333352d31302f4769744875622f6578616d706c65732f6775657374626f6f6b2f524541444d452e6d643f706978656c" alt="Analytics" data-canonical-src="https://kubernetes-site.appspot.com/UA-36037335-10/GitHub/examples/guestbook/README.md?pixel" style="max-width:100%;"></a></p>


</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.06489s from github-fe119-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
    </ul>
  </div>
</div>


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-3241a40a58a82e21daef3dd3cdca01bde189158793c1b6f9193fff2b5293cd1d.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github/index-93799dc3b48721586da77cc7c73632bc4fb8e157356876ec160370ab6be81349.js"></script>
      
      
  </body>
</html>

