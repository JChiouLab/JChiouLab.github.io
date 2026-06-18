# Local Website Setup Walkthrough

We have successfully configured your local environment and launched the Jekyll website. Here is a summary of the setup and how you can run the website in the future.

## What We Did

1. **Local Ruby Compilation**
   - Since macOS system Ruby 2.6 is deprecated and compiling native extensions fails due to Xcode version mismatch on newer macOS releases, we cloned `ruby-build` and compiled a standalone, fresh installation of **Ruby 3.1.4** to `~/local-ruby`. This installation uses your local Xcode compiler tools cleanly.
   
2. **Jekyll Configuration Fixes**
   - **Excluded Vendor Directory**: We updated the `exclude` list in [_config.yml](file:///Users/jiangeng/IPMB_ChiouLab/JChiouLab.github.io/_config.yml) to ignore `vendor`, `vendor/bundle`, `.jekyll-cache`, and `.sass-cache`. This stops Jekyll from trying to parse the gem files as website source code.
   - **Added WEBrick Dependency**: Ruby 3.0+ removed `webrick` from its default standard library, which Jekyll serve depends on. We added `gem "webrick"` to [Gemfile](file:///Users/jiangeng/IPMB_ChiouLab/JChiouLab.github.io/Gemfile) and ran `bundle install`.

3. **Launched the Web Server**
   - We started the Jekyll web server locally at `http://127.0.0.1:4000`.

---

## How to Run the Website in the Future

Whenever you want to run the website locally for development:

1. **Open a terminal in the project directory:**
   ```bash
   cd /Users/jiangeng/IPMB_ChiouLab/JChiouLab.github.io
   ```

2. **Start the server:**
   ```bash
   ~/local-ruby/bin/bundle exec jekyll serve --host 127.0.0.1 --port 4000
   ```

3. **Access the website:**
   Open [http://127.0.0.1:4000](http://127.0.0.1:4000) in your web browser. Any changes you make to markdown or layouts will automatically recompile and show up on the page.
