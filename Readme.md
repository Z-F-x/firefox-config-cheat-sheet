

Ignore chrome.css:
go into about:config
Set in the text field: 
toolkit.legacyUserProfileCustomizations.stylesheets = true 
---------------------------------------------
Find installation folder of Mullvad / Firefox / Librewolf
about:support
Go to Profile Directory | Open Directory
Create a folder called: chrome.css
Create a file called: userContent.css
---------------------------------------------
Examples where background is set to dark gray:

@-moz-document url("about:home") {
  /* Add custom styles for Firefox new tab */
    body {
        background-color: #1b1b1b !important; /* Replace #yourColorCode with your desired color */
    }
}

@-moz-document url("about:welcome") {
  /* Add custom styles for Firefox new tab */
    body {
        background-color: #1b1b1b !important; /* Replace #yourColorCode with your desired color */
    }
}


@-moz-document url("about:newtab") {
  /* Add custom styles for Firefox new tab */
    body {
        background-color: #1b1b1b !important; /* Replace #yourColorCode with your desired color */
    }
}


@-moz-document url("about:preferences"), url("about:addons") {
  /* Add custom styles for Firefox settings or addon pages */
    body {
        background-color: #1b1b1b !important; /* Replace #yourColorCode with your desired color */
    }
}



@-moz-document url-prefix("about:") {
  /* Style any about:* page, like about:config, about:support */
      body {
        background-color: #1b1b1b !important; /* Replace #yourColorCode with your desired color */
    }
}


@-moz-document domain("example.com") {
  /* Add styles for all pages on example.com */
      body {
        background-color: #1b1b1b !important; /* Replace #yourColorCode with your desired color */
    }
}



@-moz-document url-prefix("file://") {
  /* Add styles to local files */
      body {
        background-color: #1b1b1b !important; /* Replace #yourColorCode with your desired color */
    }
}



@-moz-document url-prefix("https://example.com/settings") {
  /* Style specific paths like /settings */
      body {
        background-color: #1b1b1b !important; /* Replace #yourColorCode with your desired color */
    }
}

@-moz-document url-prefix("about:home") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:newtab") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:welcome") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:preferences") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:addons") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:downloads") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:config") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:profiles") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:performance") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:plugins") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:support") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:logins") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:sync-log") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:blank") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:crashes") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:sessionrestore") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:memory") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:healthreport") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:networking") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:debugging") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:devtools") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:performance") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:telemetry") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:certificate") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:cache") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:permissions") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:robots") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:mozilla") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:blocked") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:networking") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:processes") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:policies") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:restartrequired") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:preferences#privacy") {
    body {
        background-color: #1b1b1b !important;
    }
}

@-moz-document url-prefix("about:preferences#search") {
    body {
        background-color: #1b1b1b !important;
    }
}

.sticky-container {
        background-color: #1b1b1b !important; /* Replace #yourColorCode with your desired
}

#filter{
        background-color: #1b1b1b !important; /* Replace #yourColorCode with your desired
}

#handlersView{
        background-color: #1b1b1b !important; /* Replace #yourColorCode with your desired
}

body
