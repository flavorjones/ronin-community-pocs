# Contributing

Check the [issues] for ideas on which PoC to add.

1. [Fork this repository][fork].
2. Clone your fork:

   ```shell
   git clone git@github.com:<yourusername>/community-pocs.git
   cd community-pocs/
   ```

3. install [ronin-exploits][install-ronin-exploits]
4. Generate a new exploit:

   ```shell
   ronin-exploits new exploits/<product>/CVE-YYYY-XXXX.rb
   ```

5. Fill in metadata and the `build`/`launch`/`cleanup` methods.
6. Test it!

   ```shell
   ./exploits/<product>/CVE-YYYY-XXXX.rb -p foo=bar ...
   ```

7. Commit it!

   ```shell
   git add exploits/<product>/CVE-YYYY-XXXX.rb
   git commit -m "Added PoC for CVE-YYYY-XXXX"
   ```

7. Submit your Pull Request!
8. Wait for review and feedback.
9. ????
10. Success!

[issues]: https://github.com/ronin-rb/community-pocs/issues
[fork]: https://github.com/ronin-rb/community-pocs/fork
[install-ronin-exploits]: https://github.com/ronin-rb/ronin-exploits#install
