#generic-repos is licensed under the Mulan PSL v2.
#You can use this software according to the terms and conditions of the Mulan PSL v2.
#You may obtain a copy of Mulan PSL v2 at:
#    http://license.coscl.org.cn/MulanPSL2
#THIS SOFTWARE IS PROVIDED ON AN "AS IS" BASIS, WITHOUT WARRANTIES OF ANY KIND, EITHER EXPRESS OR
#IMPLIED, INCLUDING BUT NOT LIMITED TO NON-INFRINGEMENT, MERCHANTABILITY OR FIT FOR A PARTICULAR
#PURPOSE.
#See the Mulan PSL v2 for more details.
 
[OS]
name=OS
baseurl=https://mirrors.163.com/openeuler/openEuler-24.03-LTS/OS/$basearch/
enabled=1
gpgcheck=1
gpgkey=https://mirrors.163.com/openeuler/openEuler-24.03-LTS/OS/$basearch/RPM-GPG-KEY-openEuler
 
[everything]
name=everything
baseurl=https://mirrors.163.com/openeuler/openEuler-24.03-LTS/everything/$basearch/
enabled=1
gpgcheck=1
gpgkey=https://mirrors.163.com/openeuler/openEuler-24.03-LTS/everything/$basearch/RPM-GPG-KEY-openEuler
 
[EPOL]
name=EPOL
baseurl=https://mirrors.163.com/openeuler/openEuler-24.03-LTS/EPOL/main/$basearch/
enabled=1
gpgcheck=1
gpgkey=https://mirrors.163.com/openeuler/openEuler-24.03-LTS/OS/$basearch/RPM-GPG-KEY-openEuler
 
[debuginfo]
name=debuginfo
baseurl=https://mirrors.163.com/openeuler/openEuler-24.03-LTS/debuginfo/$basearch/
enabled=1
gpgcheck=1
gpgkey=https://mirrors.163.com/openeuler/openEuler-24.03-LTS/debuginfo/$basearch/RPM-GPG-KEY-openEuler
 
[source]
name=source
baseurl=https://mirrors.163.com/openeuler/openEuler-24.03-LTS/source/
enabled=1
gpgcheck=1
gpgkey=https://mirrors.163.com/openeuler/openEuler-24.03-LTS/source/RPM-GPG-KEY-openEuler
 
[update]
name=update
baseurl=https://mirrors.163.com/openeuler/openEuler-24.03-LTS/update/$basearch/
enabled=1
gpgcheck=1
gpgkey=https://mirrors.163.com/openeuler/openEuler-24.03-LTS/OS/$basearch/RPM-GPG-KEY-openEuler
