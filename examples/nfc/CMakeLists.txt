# Copyright (C) 2022 The Qt Company Ltd.
# SPDX-License-Identifier: LicenseRef-Qt-Commercial OR BSD-3-Clause

if(TARGET Qt6::Widgets)
    qt_internal_add_example(annotatedurl)
endif()
if(TARGET Qt6::QuickControls2)
    qt_internal_add_example(ndefeditor)
endif()
