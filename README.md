# Ansible role for chruby

This role installs chruby on the remove environment(s).

## Requirements

Tested on ansible 1.6, might work (or not) on earlier versions.

## Role variables

<tt>chruby_version</tt>: the version of chruby to install (defaults to 0.3.8)

## Dependencies

Tested on ubuntu 12.04 and 14.04.
No install dependencies but works nicely with <tt>ruby-install</tt> installed,
see [ruby-install](https://galaxy.ansible.com/list#/roles/1289).

## License

All of this role is under [MIT](http://opensource.org/licenses/MIT) license.
