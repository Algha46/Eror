# Eror
❯ exec zsh
[powerlevel10k] fetching gitstatusd .. |
[ERROR]: gitstatus failed to initialize.


  Zsh log (/data/data/com.termux/files/usr/tmp/gitstatus.POWERLEVEL9K.10550.14945.1732674814.2.xtrace.log):

    +(anon):7> setopt monitor
    +(anon):9> ((  ! _GITSTATUS_STATE_POWERLEVEL9K  ))
    +(anon):10> [[ -r /proc/version ]]
    +(anon):13> print -rn
    +(anon):14> zsystem flock -f lock_fd /data/data/com.termux/files/usr/tmp/gitstatus.POWERLEVEL9K.10550.14945.1732674814.2.lock
    +(anon):15> [[ 14 == <1-> ]]
    +(anon):18> typeset -gi '_GITSTATUS_LOCK_FD_POWERLEVEL9K=lock_fd'
    +(anon):20> [[ linux-android == cygwin* ]]
    +(anon):41> sysopen -r -o cloexec -u resp_fd /proc/self/fd/13
    +(anon):44> typeset -gi 'GITSTATUS_DAEMON_PID_POWERLEVEL9K=17562'
    +(anon):46> [[ 16 == <1-> ]]
    +(anon):47> typeset -gi '_GITSTATUS_RESP_FD_POWERLEVEL9K=resp_fd'
    +(anon):41> _gitstatus_daemon_p9k_
    +(anon):48> typeset -gi '_GITSTATUS_STATE_POWERLEVEL9K=1'
    +(anon):51> ((  ! async  ))
    +(anon):52> ((  _GITSTATUS_CLIENT_PID_POWERLEVEL9K == sysparams[pid]  ))
    +(anon):54> local pgid
    +_gitstatus_daemon_p9k_:1> local -i pipe_fd
    +(anon):55> ((  0 < 20  ))
    +(anon):56> [[ -t 16 ]]
    +(anon):57> sysread -s 20 -t 10.0000000000 -i 16 'pgid[$#pgid+1]'
    +(anon):55> ((  20 < 20  ))
    +(anon):59> [[ '               17562' == \ #<1-> ]]
    +(anon):60> typeset -gi 'GITSTATUS_DAEMON_PID_POWERLEVEL9K=pgid'
    +(anon):62> sysopen -w -o cloexec -u req_fd -- /data/data/com.termux/files/usr/tmp/gitstatus.POWERLEVEL9K.10550.14945.1732674814.2.fifo
    +(anon):63> [[ 15 == <1-> ]]
    +(anon):64> typeset -gi '_GITSTATUS_REQ_FD_POWERLEVEL9K=req_fd'
    +(anon):66> print -nru 15 -- $'}hello\C-_\C-^'
    +(anon):67> local expected=$'}hello\C-_0\C-^' actual
    +(anon):68> ((  1  ))
    +(anon):68> [[ ! -t 1 ]]
    +(anon):71> local -F deadline=1
    +(anon):73> true
    +(anon):74> [[ -t 16 ]]
    +(anon):75> sysread -s 1 -t 10.0000000000 -i 16 actual
    +(anon):76> [[ $'}hello\C-_0\C-^' == * ]]
    +(anon):77> [[ $'\C-A' !=  ]]
    +(anon):85> ((  EPOCHREALTIME < deadline  ))
    +(anon):86> ((  deadline > 0  ))
    +(anon):87> deadline=0
    +(anon):88> ((  stderr_fd  ))
    +(anon):89> unsetopt xtrace

  Daemon log (/data/data/com.termux/files/usr/tmp/gitstatus.POWERLEVEL9K.10550.14945.1732674814.2.daemon.log):

    +_gitstatus_daemon_p9k_:3> local pgid=17562
    +_gitstatus_daemon_p9k_:4> [[ 17562 == <1-> ]]
    +_gitstatus_daemon_p9k_:5> cd -q /
    +_gitstatus_daemon_p9k_:90> ((  lock_fd == -1  ))
    +_gitstatus_daemon_p9k_:9> trap '' PIPE
    +_gitstatus_daemon_p9k_:11> local uname_sm
    +_gitstatus_daemon_p9k_:12> uname_sm=+_gitstatus_daemon_p9k_:12> uname -sm
    +_gitstatus_daemon_p9k_:93> zsystem flock -- /data/data/com.termux/files/usr/tmp/gitstatus.POWERLEVEL9K.10550.14945.1732674814.2.lock
    +_gitstatus_daemon_p9k_:12> uname_sm='linux aarch64'
    +_gitstatus_daemon_p9k_:13> [[ 'linux aarch64' == [^\ ]##\ [^\ ]## ]]
    +_gitstatus_daemon_p9k_:14> local uname_s=linux
    +_gitstatus_daemon_p9k_:15> local uname_m=aarch64
    +_gitstatus_daemon_p9k_:17> [[ '' == <1-> ]]
    +_gitstatus_daemon_p9k_:20> local cpus
    +_gitstatus_daemon_p9k_:21> ((  ! 1  ))
    +_gitstatus_daemon_p9k_:21> [[ linux == linux ]]
    +_gitstatus_daemon_p9k_:23> ((  ! 0  ))
    +_gitstatus_daemon_p9k_:24> cpus=8
    +_gitstatus_daemon_p9k_:27> args+=( -t 16 )
    +_gitstatus_daemon_p9k_:30> mkfifo -- /data/data/com.termux/files/usr/tmp/gitstatus.POWERLEVEL9K.10550.14945.1732674814.2.fifo
    +_gitstatus_daemon_p9k_:31> print -rnu 15 -- '               17562'
    +_gitstatus_daemon_p9k_:33> zf_rm -- /data/data/com.termux/files/usr/tmp/gitstatus.POWERLEVEL9K.10550.14945.1732674814.2.fifo
    +_gitstatus_daemon_p9k_:35> local _gitstatus_zsh_daemon _gitstatus_zsh_version _gitstatus_zsh_downloaded
    +_gitstatus_daemon_p9k_:43> local gitstatus_plugin_dir_var=_gitstatus_plugin_dir_p9k_
    +_gitstatus_daemon_p9k_:44> local gitstatus_plugin_dir=/data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus
    +_gitstatus_daemon_p9k_:45> set -- -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_daemon_p9k_:47> [[ 1 == (|-|+)<1-> ]]
    +_gitstatus_daemon_p9k_:48> source /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/install
    +/data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/install:472> [ -z '' ']'
    +/data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/install:473> _gitstatus_install_main /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:1> [ -n 5.9 ']'
    +_gitstatus_install_main:2> emulate -L sh -o no_unset
    +_gitstatus_install_main:7> local argv1=/data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus
    +_gitstatus_install_main:8> shift
    +_gitstatus_install_main:10> local no_check='' no_install='' uname_s='' uname_m='' gitstatus_dir='' dl_status='' e=''
    +_gitstatus_install_main:11> local opt='' OPTARG='' OPTIND=1
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case d (h)
    +_gitstatus_install_main:14> case d (n)
    +_gitstatus_install_main:14> case d (f)
    +_gitstatus_install_main:14> case d (d)
    +_gitstatus_install_main:55> [ -n '' ']'
    +_gitstatus_install_main:59> [ -z /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus ']'
    +_gitstatus_install_main:63> gitstatus_dir=/data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case s (h)
    +_gitstatus_install_main:14> case s (n)
    +_gitstatus_install_main:14> case s (f)
    +_gitstatus_install_main:14> case s (d)
    +_gitstatus_install_main:14> case s (p)
    +_gitstatus_install_main:14> case s (e)
    +_gitstatus_install_main:14> case s (m)
    +_gitstatus_install_main:14> case s (s)
    +_gitstatus_install_main:99> [ -n '' ']'
    +_gitstatus_install_main:103> [ -z linux ']'
    +_gitstatus_install_main:107> uname_s=linux
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case m (h)
    +_gitstatus_install_main:14> case m (n)
    +_gitstatus_install_main:14> case m (f)
    +_gitstatus_install_main:14> case m (d)
    +_gitstatus_install_main:14> case m (p)
    +_gitstatus_install_main:14> case m (e)
    +_gitstatus_install_main:14> case m (m)
    +_gitstatus_install_main:88> [ -n '' ']'
    +_gitstatus_install_main:92> [ -z aarch64 ']'
    +_gitstatus_install_main:96> uname_m=aarch64
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case p (h)
    +_gitstatus_install_main:14> case p (n)
    +_gitstatus_install_main:14> case p (f)
    +_gitstatus_install_main:14> case p (d)
    +_gitstatus_install_main:14> case p (p)
    +_gitstatus_install_main:66> [ -n '' ']'
    +_gitstatus_install_main:70> [ -z 'printf '\''\001'\'' >&15' ']'
    +_gitstatus_install_main:74> dl_status='printf '\''\001'\'' >&15'
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case e (h)
    +_gitstatus_install_main:14> case e (n)
    +_gitstatus_install_main:14> case e (f)
    +_gitstatus_install_main:14> case e (d)
    +_gitstatus_install_main:14> case e (p)
    +_gitstatus_install_main:14> case e (e)
    +_gitstatus_install_main:77> [ -n '' ']'
    +_gitstatus_install_main:81> [ -z 15 ']'
    +_gitstatus_install_main:85> e=15
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:115> shift 11
    +_gitstatus_install_main:117> : 15
    +_gitstatus_install_main:118> : /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus
    +_gitstatus_install_main:120> [ -n '' -a -n '' ']'
    +_gitstatus_install_main:125> [ -z linux ']'
    +_gitstatus_install_main:129> [ -z aarch64 ']'
    +_gitstatus_install_main:134> local daemon=''
    +_gitstatus_install_main:135> local cache_dir=/data/data/com.termux/files/home/.cache/gitstatus
    +_gitstatus_install_main:137> [ -z '' ']'
    +_gitstatus_install_main:138> [ -n '' ']'
    +_gitstatus_install_main:142> [ -z '' -a -e /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/usrbin/gitstatusd ']'
    +_gitstatus_install_main:145> [ -n '' ']'
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="cygwin_nt-10.0"; uname_m_glob="i686";    file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="cygwin_nt-10.0"; uname_m_glob="i686";    file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="cygwin_nt-10.0"; uname_m_glob="i686";    file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3";'
    +_gitstatus_install_main:166> uname_s_glob=cygwin_nt-10.0
    +_gitstatus_install_main:166> uname_m_glob=i686
    +_gitstatus_install_main:166> file=gitstatusd-linux-aarch64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3
    +_gitstatus_install_main:168> [ -z cygwin_nt-10.0 -o -z i686 -o -z gitstatusd-linux-aarch64 -o -z v1.5.4 -o -z 5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3 ']'
    +_gitstatus_install_main:177> case linux (cygwin_nt-10.0)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="cygwin_nt-10.0"; uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="cygwin_nt-10.0"; uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="cygwin_nt-10.0"; uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f";'
    +_gitstatus_install_main:166> uname_s_glob=cygwin_nt-10.0
    +_gitstatus_install_main:166> uname_m_glob=x86_64
    +_gitstatus_install_main:166> file=gitstatusd-linux-aarch64
    +_gitstatus_install_main:166> version=v1.5.1
    +_gitstatus_install_main:166> sha256=c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f
    +_gitstatus_install_main:168> [ -z cygwin_nt-10.0 -o -z x86_64 -o -z gitstatusd-linux-aarch64 -o -z v1.5.1 -o -z c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f ']'
    +_gitstatus_install_main:177> case linux (cygwin_nt-10.0)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="darwin";         uname_m_glob="arm64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="darwin";         uname_m_glob="arm64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="darwin";         uname_m_glob="arm64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a";'
    +_gitstatus_install_main:166> uname_s_glob=darwin
    +_gitstatus_install_main:166> uname_m_glob=arm64
    +_gitstatus_install_main:166> file=gitstatusd-linux-aarch64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a
    +_gitstatus_install_main:168> [ -z darwin -o -z arm64 -o -z gitstatusd-linux-aarch64 -o -z v1.5.4 -o -z eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a ']'
    +_gitstatus_install_main:177> case linux (darwin)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="darwin";         uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="darwin";         uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="darwin";         uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6";'
    +_gitstatus_install_main:166> uname_s_glob=darwin
    +_gitstatus_install_main:166> uname_m_glob=x86_64
    +_gitstatus_install_main:166> file=gitstatusd-linux-aarch64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6
    +_gitstatus_install_main:168> [ -z darwin -o -z x86_64 -o -z gitstatusd-linux-aarch64 -o -z v1.5.4 -o -z 9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6 ']'
    +_gitstatus_install_main:177> case linux (darwin)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="freebsd";        uname_m_glob="amd64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="freebsd";        uname_m_glob="amd64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="freebsd";        uname_m_glob="amd64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442";'
    +_gitstatus_install_main:166> uname_s_glob=freebsd
    +_gitstatus_install_main:166> uname_m_glob=amd64
    +_gitstatus_install_main:166> file=gitstatusd-linux-aarch64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442
    +_gitstatus_install_main:168> [ -z freebsd -o -z amd64 -o -z gitstatusd-linux-aarch64 -o -z v1.5.4 -o -z 8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442 ']'
    +_gitstatus_install_main:177> case linux (freebsd)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="linux";          uname_m_glob="aarch64"; file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="linux";          uname_m_glob="aarch64"; file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="linux";          uname_m_glob="aarch64"; file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225";'
    +_gitstatus_install_main:166> uname_s_glob=linux
    +_gitstatus_install_main:166> uname_m_glob=aarch64
    +_gitstatus_install_main:166> file=gitstatusd-linux-aarch64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225
    +_gitstatus_install_main:168> [ -z linux -o -z aarch64 -o -z gitstatusd-linux-aarch64 -o -z v1.5.4 -o -z 32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225 ']'
    +_gitstatus_install_main:177> case linux (linux)
    +_gitstatus_install_main:181> case aarch64 (aarch64)
    +_gitstatus_install_main:188> [ -z '' ']'
    +_gitstatus_install_main:190> local daemon=/data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/usrbin/gitstatusd-linux-aarch64
    +_gitstatus_install_main:191> [ ! -e /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/usrbin/gitstatusd-linux-aarch64 ']'
    +_gitstatus_install_main:192> daemon=/data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64
    +_gitstatus_install_main:193> [ -e /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64 ']'
    +_gitstatus_install_main:195> [ -n /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64 ']'
    +_gitstatus_install_main:196> _gitstatus_install_daemon_found 0 _gitstatus_set_daemon_p9k_
    +_gitstatus_install_daemon_found:1> local installed=0
    +_gitstatus_install_daemon_found:2> shift
    +_gitstatus_install_daemon_found:3> [ 1 '=' 0 ']'
    +_gitstatus_install_daemon_found:3> _gitstatus_set_daemon_p9k_ /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64 v1.5.4 0
    +_gitstatus_set_daemon_p9k_:1> _gitstatus_zsh_daemon=/data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64
    +_gitstatus_set_daemon_p9k_:2> _gitstatus_zsh_version=v1.5.4
    +_gitstatus_set_daemon_p9k_:3> _gitstatus_zsh_downloaded=0
    +_gitstatus_install_main:197> return
    +_gitstatus_daemon_p9k_:49> [[ -n /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64 ]]
    +_gitstatus_daemon_p9k_:50> [[ -n v1.5.4 ]]
    +_gitstatus_daemon_p9k_:51> [[ 0 == [01] ]]
    +_gitstatus_daemon_p9k_:53> ((  UID == EUID  ))
    +_gitstatus_daemon_p9k_:54> local home=/data/data/com.termux/files/home
    +_gitstatus_daemon_p9k_:62> [[ -x /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64 ]]
    +_gitstatus_daemon_p9k_:63> HOME=/data/data/com.termux/files/home /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64 -G v1.5.4 -s -1 -u -1 -d -1 -c -1 -m -1 -v DEBUG -t 16
    Could not find a PHDR: broken executable?
    +_gitstatus_daemon_p9k_:64> local -i ret=134
    +_gitstatus_daemon_p9k_:65> [[ 134 == (0|129|130|131|137|141|143|159) ]]
    +_gitstatus_daemon_p9k_:68> ((  ! _gitstatus_zsh_downloaded  ))
    +_gitstatus_daemon_p9k_:69> [[ 1 == (|-|+)<1-> ]]
    +_gitstatus_daemon_p9k_:70> [[ /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64 == /data/data/com.termux/files/home/.cache/gitstatus/* ]]
    +_gitstatus_daemon_p9k_:73> set -- -f -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_daemon_p9k_:74> _gitstatus_zsh_daemon=''
    +_gitstatus_daemon_p9k_:75> _gitstatus_zsh_version=''
    +_gitstatus_daemon_p9k_:76> _gitstatus_zsh_downloaded=''
    +_gitstatus_daemon_p9k_:77> source /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/install
    +/data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/install:472> [ -z '' ']'
    +/data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus/install:473> _gitstatus_install_main /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -f -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:1> [ -n 5.9 ']'
    +_gitstatus_install_main:2> emulate -L sh -o no_unset
    +_gitstatus_install_main:7> local argv1=/data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus
    +_gitstatus_install_main:8> shift
    +_gitstatus_install_main:10> local no_check='' no_install='' uname_s='' uname_m='' gitstatus_dir='' dl_status='' e=''
    +_gitstatus_install_main:11> local opt='' OPTARG='' OPTIND=1
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -f -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case f (h)
    +_gitstatus_install_main:14> case f (n)
    +_gitstatus_install_main:14> case f (f)
    +_gitstatus_install_main:48> [ -n '' ']'
    +_gitstatus_install_main:52> no_check=1
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -f -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case d (h)
    +_gitstatus_install_main:14> case d (n)
    +_gitstatus_install_main:14> case d (f)
    +_gitstatus_install_main:14> case d (d)
    +_gitstatus_install_main:55> [ -n '' ']'
    +_gitstatus_install_main:59> [ -z /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus ']'
    +_gitstatus_install_main:63> gitstatus_dir=/data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -f -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case s (h)
    +_gitstatus_install_main:14> case s (n)
    +_gitstatus_install_main:14> case s (f)
    +_gitstatus_install_main:14> case s (d)
    +_gitstatus_install_main:14> case s (p)
    +_gitstatus_install_main:14> case s (e)
    +_gitstatus_install_main:14> case s (m)
    +_gitstatus_install_main:14> case s (s)
    +_gitstatus_install_main:99> [ -n '' ']'
    +_gitstatus_install_main:103> [ -z linux ']'
    +_gitstatus_install_main:107> uname_s=linux
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -f -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case m (h)
    +_gitstatus_install_main:14> case m (n)
    +_gitstatus_install_main:14> case m (f)
    +_gitstatus_install_main:14> case m (d)
    +_gitstatus_install_main:14> case m (p)
    +_gitstatus_install_main:14> case m (e)
    +_gitstatus_install_main:14> case m (m)
    +_gitstatus_install_main:88> [ -n '' ']'
    +_gitstatus_install_main:92> [ -z aarch64 ']'
    +_gitstatus_install_main:96> uname_m=aarch64
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -f -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case p (h)
    +_gitstatus_install_main:14> case p (n)
    +_gitstatus_install_main:14> case p (f)
    +_gitstatus_install_main:14> case p (d)
    +_gitstatus_install_main:14> case p (p)
    +_gitstatus_install_main:66> [ -n '' ']'
    +_gitstatus_install_main:70> [ -z 'printf '\''\001'\'' >&15' ']'
    +_gitstatus_install_main:74> dl_status='printf '\''\001'\'' >&15'
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -f -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:14> case e (h)
    +_gitstatus_install_main:14> case e (n)
    +_gitstatus_install_main:14> case e (f)
    +_gitstatus_install_main:14> case e (d)
    +_gitstatus_install_main:14> case e (p)
    +_gitstatus_install_main:14> case e (e)
    +_gitstatus_install_main:77> [ -n '' ']'
    +_gitstatus_install_main:81> [ -z 15 ']'
    +_gitstatus_install_main:85> e=15
    +_gitstatus_install_main:13> getopts :s:m:d:p:e:fnh opt -f -d /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus -s linux -m aarch64 -p 'printf '\''\001'\'' >&15' -e 15 -- _gitstatus_set_daemon_p9k_
    +_gitstatus_install_main:115> shift 12
    +_gitstatus_install_main:117> : 15
    +_gitstatus_install_main:118> : /data/data/com.termux/files/home/.oh-my-zsh/custom/themes/powerlevel10k/gitstatus
    +_gitstatus_install_main:120> [ -n 1 -a -n '' ']'
    +_gitstatus_install_main:125> [ -z linux ']'
    +_gitstatus_install_main:129> [ -z aarch64 ']'
    +_gitstatus_install_main:134> local daemon=''
    +_gitstatus_install_main:135> local cache_dir=/data/data/com.termux/files/home/.cache/gitstatus
    +_gitstatus_install_main:137> [ -z 1 ']'
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line=''
    +_gitstatus_install_main:163> [ -n '' ']'
    +_gitstatus_install_main:163> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="cygwin_nt-10.0"; uname_m_glob="i686";    file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="cygwin_nt-10.0"; uname_m_glob="i686";    file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="cygwin_nt-10.0"; uname_m_glob="i686";    file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3";'
    +_gitstatus_install_main:166> uname_s_glob=cygwin_nt-10.0
    +_gitstatus_install_main:166> uname_m_glob=i686
    +_gitstatus_install_main:166> file=gitstatusd-linux-aarch64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3
    +_gitstatus_install_main:168> [ -z cygwin_nt-10.0 -o -z i686 -o -z gitstatusd-linux-aarch64 -o -z v1.5.4 -o -z 5a8a809dcebdb6aa9b47d37e086c0485424a9d9c136770eec3c26cedf5bb75e3 ']'
    +_gitstatus_install_main:177> case linux (cygwin_nt-10.0)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="cygwin_nt-10.0"; uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="cygwin_nt-10.0"; uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="cygwin_nt-10.0"; uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.1"; sha256="c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f";'
    +_gitstatus_install_main:166> uname_s_glob=cygwin_nt-10.0
    +_gitstatus_install_main:166> uname_m_glob=x86_64
    +_gitstatus_install_main:166> file=gitstatusd-linux-aarch64
    +_gitstatus_install_main:166> version=v1.5.1
    +_gitstatus_install_main:166> sha256=c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f
    +_gitstatus_install_main:168> [ -z cygwin_nt-10.0 -o -z x86_64 -o -z gitstatusd-linux-aarch64 -o -z v1.5.1 -o -z c84cade0d6b86e04c27a6055f45851f6b46d6b88ba58772f7ca8ef4d295c800f ']'
    +_gitstatus_install_main:177> case linux (cygwin_nt-10.0)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="darwin";         uname_m_glob="arm64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="darwin";         uname_m_glob="arm64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="darwin";         uname_m_glob="arm64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a";'
    +_gitstatus_install_main:166> uname_s_glob=darwin
    +_gitstatus_install_main:166> uname_m_glob=arm64
    +_gitstatus_install_main:166> file=gitstatusd-linux-aarch64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a
    +_gitstatus_install_main:168> [ -z darwin -o -z arm64 -o -z gitstatusd-linux-aarch64 -o -z v1.5.4 -o -z eae979e990ca37c56ee39fadd0c3f392cbbd0c6bdfb9a603010be60d9e48910a ']'
    +_gitstatus_install_main:177> case linux (darwin)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="darwin";         uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="darwin";         uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="darwin";         uname_m_glob="x86_64";  file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6";'
    +_gitstatus_install_main:166> uname_s_glob=darwin
    +_gitstatus_install_main:166> uname_m_glob=x86_64
    +_gitstatus_install_main:166> file=gitstatusd-linux-aarch64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6
    +_gitstatus_install_main:168> [ -z darwin -o -z x86_64 -o -z gitstatusd-linux-aarch64 -o -z v1.5.4 -o -z 9fd3913ec1b6b856ab6e08a99a2343f0e8e809eb6b62ca4b0963163656c668e6 ']'
    +_gitstatus_install_main:177> case linux (darwin)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="freebsd";        uname_m_glob="amd64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="freebsd";        uname_m_glob="amd64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="freebsd";        uname_m_glob="amd64";   file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442";'
    +_gitstatus_install_main:166> uname_s_glob=freebsd
    +_gitstatus_install_main:166> uname_m_glob=amd64
    +_gitstatus_install_main:166> file=gitstatusd-linux-aarch64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442
    +_gitstatus_install_main:168> [ -z freebsd -o -z amd64 -o -z gitstatusd-linux-aarch64 -o -z v1.5.4 -o -z 8e57ad642251e5acfa430aed82cd4ffe103db0bfadae4a15ccaf462c455d0442 ']'
    +_gitstatus_install_main:177> case linux (freebsd)
    +_gitstatus_install_main:177> case linux (*)
    +_gitstatus_install_main:179> continue
    +_gitstatus_install_main:161> IFS='' +_gitstatus_install_main:161> read -r line
    +_gitstatus_install_main:162> line='uname_s_glob="linux";          uname_m_glob="aarch64"; file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225";'
    +_gitstatus_install_main:163> [ -n 'uname_s_glob="linux";          uname_m_glob="aarch64"; file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225";' ']'
    +_gitstatus_install_main:165> local uname_s_glob='' uname_m_glob='' file='' version='' sha256=''
    +_gitstatus_install_main:166> eval 'uname_s_glob="linux";          uname_m_glob="aarch64"; file="gitstatusd-${uname_s}-${uname_m}";     version="v1.5.4"; sha256="32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225";'
    +_gitstatus_install_main:166> uname_s_glob=linux
    +_gitstatus_install_main:166> uname_m_glob=aarch64
    +_gitstatus_install_main:166> file=gitstatusd-linux-aarch64
    +_gitstatus_install_main:166> version=v1.5.4
    +_gitstatus_install_main:166> sha256=32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225
    +_gitstatus_install_main:168> [ -z linux -o -z aarch64 -o -z gitstatusd-linux-aarch64 -o -z v1.5.4 -o -z 32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225 ']'
    +_gitstatus_install_main:177> case linux (linux)
    +_gitstatus_install_main:181> case aarch64 (aarch64)
    +_gitstatus_install_main:188> [ -z 1 ']'
    +_gitstatus_install_main:203> [ -n '' ']'
    +_gitstatus_install_main:208> local daemon=/data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64
    +_gitstatus_install_main:210> [ -n '' ']'
    +_gitstatus_install_main:214> [ ! -d /data/data/com.termux/files/home/.cache/gitstatus ']'
    +_gitstatus_install_main:214> [ ! -w /data/data/com.termux/files/home/.cache/gitstatus ']'
    +_gitstatus_install_main:237> [ -n /data/data/com.termux/files/usr/tmp -a '(' '(' -d /data/data/com.termux/files/usr/tmp -a -w /data/data/com.termux/files/usr/tmp ')' -o ! '(' -d /tmp -a -w /tmp ')' ')' ']'
    +_gitstatus_install_main:238> local tmp=/data/data/com.termux/files/usr/tmp
    +_gitstatus_install_main:242> command -v mktemp
    +_gitstatus_install_main:243> tmpdir=+_gitstatus_install_main:243> mktemp -d /data/data/com.termux/files/usr/tmp/gitstatus-install.XXXXXXXXXX
    +_gitstatus_install_main:243> tmpdir=/data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S
    +_gitstatus_install_main:268> command -v curl
    +_gitstatus_install_main:325> local url1=https://github.com/romkatv/gitstatus/releases/download/v1.5.4/gitstatusd-linux-aarch64.tar.gz
    +_gitstatus_install_main:326> local url2=https://gitee.com/romkatv/gitstatus/raw/release-v1.5.4/release/gitstatusd-linux-aarch64.tar.gz
    +_gitstatus_install_main:327> local sig='INT QUIT TERM ILL PIPE'
    +_gitstatus_install_main:363> local trapped=''
    +_gitstatus_install_main:364> trap 'trapped=1' INT QUIT TERM ILL PIPE
    +_gitstatus_install_main:366> local pid1=17577
    +_gitstatus_install_main:365> fetch 1 https://github.com/romkatv/gitstatus/releases/download/v1.5.4/gitstatusd-linux-aarch64.tar.gz
    +fetch:1> [ 1 '!=' 1 ']'
    +fetch:7> local cmd part url ret
    +fetch:8> cmd=curl -kfsSL
    +fetch:9> part=0
    +fetch:10> true
    +fetch:11> [ 0 '=' 2 ']'
    +fetch:14> [ 0 '=' 0 ']'
    +fetch:15> url=https://github.com/romkatv/gitstatus/releases/download/v1.5.4/gitstatusd-linux-aarch64.tar.gz
    +fetch:19> run_cmd curl -kfsSL -- https://github.com/romkatv/gitstatus/releases/download/v1.5.4/gitstatusd-linux-aarch64.tar.gz
    +run_cmd:1> command -v curl
    +run_cmd:2> local trapped='' pid die ret
    +run_cmd:3> trap 'trapped=1' INT QUIT TERM ILL PIPE
    +_gitstatus_install_main:367> fetch 2 https://gitee.com/romkatv/gitstatus/raw/release-v1.5.4/release/gitstatusd-linux-aarch64.tar.gz
    +fetch:1> [ 2 '!=' 1 ']'
    +fetch:1> command -v sleep
    +_gitstatus_install_main:368> local pid2=17578
    +_gitstatus_install_main:370> local die='trap - INT QUIT TERM ILL PIPE; kill -- 17577 17578 2>/dev/null; wait -- 17577 17578 2>/dev/null; exit 1'
    +_gitstatus_install_main:371> trap 'trap - INT QUIT TERM ILL PIPE; kill -- 17577 17578 2>/dev/null; wait -- 17577 17578 2>/dev/null; exit 1' INT QUIT TERM ILL PIPE
    +fetch:2> run_cmd sleep 2
    +_gitstatus_install_main:372> [ -z '' ']'
    +run_cmd:1> command -v sleep
    +_gitstatus_install_main:374> local n=''
    +run_cmd:2> local trapped='' pid die ret
    +_gitstatus_install_main:375> true
    +_gitstatus_install_main:376> [ -z 'printf '\''\001'\'' >&15' ']'
    +_gitstatus_install_main:376> eval 'printf '\''\001'\'' >&15'
    +run_cmd:3> trap 'trapped=1' INT QUIT TERM ILL PIPE
    +_gitstatus_install_main:376> printf '\001'
    +_gitstatus_install_main:377> command -v sleep
    +_gitstatus_install_main:378> sleep 1
    +run_cmd:6> curl -kfsSL -- https://github.com/romkatv/gitstatus/releases/download/v1.5.4/gitstatusd-linux-aarch64.tar.gz
    +run_cmd:7> ret=0
    +run_cmd:8> [ 0 '=' 0 ']'
    +run_cmd:9> pid=17579
    +run_cmd:10> die='trap - INT QUIT TERM ILL PIPE; kill -- 17579 2>/dev/null; wait -- 17579 2>/dev/null; exit 1'
    +run_cmd:11> trap 'trap - INT QUIT TERM ILL PIPE; kill -- 17579 2>/dev/null; wait -- 17579 2>/dev/null; exit 1' INT QUIT TERM ILL PIPE
    +run_cmd:12> [ -z '' ']'
    +run_cmd:7> ret=0
    +run_cmd:13> wait -- 17579
    +run_cmd:8> [ 0 '=' 0 ']'
    +run_cmd:9> pid=17580
    +run_cmd:10> die='trap - INT QUIT TERM ILL PIPE; kill -- 17580 2>/dev/null; wait -- 17580 2>/dev/null; exit 1'
    +run_cmd:11> trap 'trap - INT QUIT TERM ILL PIPE; kill -- 17580 2>/dev/null; wait -- 17580 2>/dev/null; exit 1' INT QUIT TERM ILL PIPE
    +run_cmd:12> [ -z '' ']'
    +run_cmd:13> wait -- 17580
    +run_cmd:6> sleep 2
    +_gitstatus_install_main:382> [ -n 17577 -a -e /data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S/1.status ']'
    +_gitstatus_install_main:399> [ -n 17578 -a -e /data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S/2.status ']'
    +_gitstatus_install_main:375> true
    +_gitstatus_install_main:376> [ -z 'printf '\''\001'\'' >&15' ']'
    +_gitstatus_install_main:376> eval 'printf '\''\001'\'' >&15'
    +_gitstatus_install_main:376> printf '\001'
    +_gitstatus_install_main:377> command -v sleep
    +_gitstatus_install_main:378> sleep 1
    +run_cmd:14> ret=0
    +run_cmd:16> trap - INT QUIT TERM ILL PIPE
    +run_cmd:17> [ -z '' ']'
    +run_cmd:18> return 0
    +fetch:7> local cmd part url ret
    +fetch:8> cmd=curl -kfsSL
    +fetch:9> part=0
    +fetch:10> true
    +fetch:11> [ 0 '=' 2 ']'
    +fetch:14> [ 0 '=' 0 ']'
    +fetch:15> url=https://gitee.com/romkatv/gitstatus/raw/release-v1.5.4/release/gitstatusd-linux-aarch64.tar.gz
    +fetch:19> run_cmd curl -kfsSL -- https://gitee.com/romkatv/gitstatus/raw/release-v1.5.4/release/gitstatusd-linux-aarch64.tar.gz
    +run_cmd:1> command -v curl
    +run_cmd:2> local trapped='' pid die ret
    +run_cmd:3> trap 'trapped=1' INT QUIT TERM ILL PIPE
    +run_cmd:6> curl -kfsSL -- https://gitee.com/romkatv/gitstatus/raw/release-v1.5.4/release/gitstatusd-linux-aarch64.tar.gz
    +run_cmd:7> ret=0
    +run_cmd:8> [ 0 '=' 0 ']'
    +run_cmd:9> pid=17596
    +run_cmd:10> die='trap - INT QUIT TERM ILL PIPE; kill -- 17596 2>/dev/null; wait -- 17596 2>/dev/null; exit 1'
    +run_cmd:11> trap 'trap - INT QUIT TERM ILL PIPE; kill -- 17596 2>/dev/null; wait -- 17596 2>/dev/null; exit 1' INT QUIT TERM ILL PIPE
    +run_cmd:12> [ -z '' ']'
    +run_cmd:13> wait -- 17596
    +_gitstatus_install_main:382> [ -n 17577 -a -e /data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S/1.status ']'
    +_gitstatus_install_main:399> [ -n 17578 -a -e /data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S/2.status ']'
    +_gitstatus_install_main:375> true
    +_gitstatus_install_main:376> [ -z 'printf '\''\001'\'' >&15' ']'
    +_gitstatus_install_main:376> eval 'printf '\''\001'\'' >&15'
    +_gitstatus_install_main:376> printf '\001'
    +_gitstatus_install_main:377> command -v sleep
    +_gitstatus_install_main:378> sleep 1
    +run_cmd:14> ret=0
    +run_cmd:16> trap - INT QUIT TERM ILL PIPE
    +run_cmd:17> [ -z '' ']'
    +run_cmd:18> return 0
    +fetch:20> ret=0
    +fetch:21> [ 0 '=' 0 ']'
    +fetch:22> check_sha256 1
    +check_sha256:1> local data_file=/data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S/1.tar.gz
    +check_sha256:2> local hash_file=/data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S/1.tar.gz.sha256
    +check_sha256:3> local hash=''
    +check_sha256:5> command -v shasum
    +check_sha256:11> command -v sha256sum
    +check_sha256:12> run_cmd sha256sum -b -- /data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S/1.tar.gz
    +run_cmd:1> command -v sha256sum
    +run_cmd:2> local trapped='' pid die ret
    +run_cmd:3> trap 'trapped=1' INT QUIT TERM ILL PIPE
    +run_cmd:7> ret=0
    +run_cmd:8> [ 0 '=' 0 ']'
    +run_cmd:6> sha256sum -b -- /data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S/1.tar.gz
    +run_cmd:9> pid=17602
    +run_cmd:10> die='trap - INT QUIT TERM ILL PIPE; kill -- 17602 2>/dev/null; wait -- 17602 2>/dev/null; exit 1'
    +run_cmd:11> trap 'trap - INT QUIT TERM ILL PIPE; kill -- 17602 2>/dev/null; wait -- 17602 2>/dev/null; exit 1' INT QUIT TERM ILL PIPE
    +run_cmd:12> [ -z '' ']'
    +run_cmd:13> wait -- 17602
    +run_cmd:14> ret=0
    +run_cmd:16> trap - INT QUIT TERM ILL PIPE
    +run_cmd:17> [ -z '' ']'
    +run_cmd:18> return 0
    +check_sha256:13> IFS='' +check_sha256:13> read -r hash
    +check_sha256:14> hash=32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225
    +check_sha256:15> [ 64 -eq 64 ']'
    +check_sha256:27> [ 1 '=' 1 -a -z 32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225 -o 32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225 '=' 32b57eb28bf6d80b280e4020a0045184f8ca897b20b570c12948aa6838673225 ']'
    +fetch:22> break
    +fetch:25> [ 0 '=' 0 ']'
    +fetch:25> break
    +fetch:30> echo -n
    +fetch:31> return 0
    +_gitstatus_install_main:382> [ -n 17577 -a -e /data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S/1.status ']'
    +_gitstatus_install_main:383> wait -- 17577
    +_gitstatus_install_main:384> local ret=0
    +_gitstatus_install_main:385> pid1=''
    +_gitstatus_install_main:386> [ 0 '=' 0 ']'
    +_gitstatus_install_main:387> [ -n 17578 ']'
    +_gitstatus_install_main:388> kill -- 17578
    +run_cmd:13> trap - INT QUIT TERM ILL PIPE
    +run_cmd:13> kill -- 17596
    +run_cmd:13> wait -- 17596
    +_gitstatus_install_main:389> wait -- 17578
    +run_cmd:13> exit 1
    +_p9k_worker_cleanup:2> emulate -L zsh
    +_p9k_worker_cleanup:3> [[ 14945 == 17578 ]]
    +_p9k_worker_cleanup:4> return 0
    +_gitstatus_install_main:391> n=1
    +_gitstatus_install_main:392> break
    +_gitstatus_install_main:419> trap - INT QUIT TERM ILL PIPE
    +_gitstatus_install_main:421> [ -z 1 ']'
    +_gitstatus_install_main:431> tar -C /data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S -xzf /data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S/1.tar.gz
    +_gitstatus_install_main:433> local tmpfile
    +_gitstatus_install_main:434> command -v mktemp
    +_gitstatus_install_main:435> tmpfile=+_gitstatus_install_main:435> mktemp /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd.XXXXXXXXXX
    +_gitstatus_install_main:435> tmpfile=/data/data/com.termux/files/home/.cache/gitstatus/gitstatusd.rN0RSLI7z3
    +_gitstatus_install_main:439> mv -f -- /data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S/gitstatusd-linux-aarch64 /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd.rN0RSLI7z3
    +_gitstatus_install_main:440> mv -f -- /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd.rN0RSLI7z3 /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64
    +_gitstatus_install_main:440> exit
    +_p9k_worker_cleanup:2> emulate -L zsh
    +_p9k_worker_cleanup:3> [[ 14945 == 17576 ]]
    +_p9k_worker_cleanup:4> return 0
    +_gitstatus_install_main:447> local ret=0
    +_gitstatus_install_main:448> rm -rf -- /data/data/com.termux/files/usr/tmp/gitstatus-install.JcfDqqio8S
    +_gitstatus_install_main:449> [ 0 '=' 0 ']'
    +_gitstatus_install_main:451> _gitstatus_install_daemon_found 1 _gitstatus_set_daemon_p9k_
    +_gitstatus_install_daemon_found:1> local installed=1
    +_gitstatus_install_daemon_found:2> shift
    +_gitstatus_install_daemon_found:3> [ 1 '=' 0 ']'
    +_gitstatus_install_daemon_found:3> _gitstatus_set_daemon_p9k_ /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64 v1.5.4 1
    +_gitstatus_set_daemon_p9k_:1> _gitstatus_zsh_daemon=/data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64
    +_gitstatus_set_daemon_p9k_:2> _gitstatus_zsh_version=v1.5.4
    +_gitstatus_set_daemon_p9k_:3> _gitstatus_zsh_downloaded=1
    +_gitstatus_install_main:452> return
    +_gitstatus_daemon_p9k_:78> [[ -n /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64 ]]
    +_gitstatus_daemon_p9k_:79> [[ -n v1.5.4 ]]
    +_gitstatus_daemon_p9k_:80> [[ 1 == 1 ]]
    +_gitstatus_daemon_p9k_:82> HOME=/data/data/com.termux/files/home /data/data/com.termux/files/home/.cache/gitstatus/gitstatusd-linux-aarch64 -G v1.5.4 -s -1 -u -1 -d -1 -c -1 -m -1 -v DEBUG -t 16
    Could not find a PHDR: broken executable?
    +_gitstatus_daemon_p9k_:84> local -i ret=134
    +_gitstatus_daemon_p9k_:85> zf_rm -f -- /data/data/com.termux/files/usr/tmp/gitstatus.POWERLEVEL9K.10550.14945.1732674814.2.lock /data/data/com.termux/files/usr/tmp/gitstatus.POWERLEVEL9K.10550.14945.1732674814.2.fifo
    +_gitstatus_daemon_p9k_:86> kill -- -17562

  System information:

    zsh:      5.9
    uname -a: Linux localhost 5.15.123-android13-8-00044-g5682afbff3e0-ab11501453 #1 SMP PREEMPT Mon Feb 26 08:40:48 UTC 2024 aarch64 Android

  If you need help, open an issue and attach this whole error message to it:

    https://github.com/romkatv/gitstatus/issues/new
