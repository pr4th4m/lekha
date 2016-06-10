#### Tips and Tricks


- Search and replace in entire project

        # search and fill buffer
        args **/*.py

        # replace and update
        argdo %s/original/target/ge | update


- Remove blank lines

        :g/^$/d


- Startup time profiling

        vim --startuptime vim.log


- Complete profiling

        :profile start profile.log
        :profile func *
        :profile file *
        :profile pause
        # Note - be patient
